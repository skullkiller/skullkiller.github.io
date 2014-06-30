SSAS – Performance maintenance powershell script
================================================

*Some years ago I was learning powershell while trying to automate some SSAS performance maintenance. This script came up as the solution. Since then I updated it to accommodate some extra needs. I’ll be updating this script with new functionalities as often as I need or remember something interesting to add.*

Hi

Some years ago I was learning powershell while trying to automate some SSAS performance maintenance. This script came up as the solution. Since then I updated it to accommodate some extra needs. I’ll be updating this script with new functionalities as often as I need or remember something interesting to add.

Any suggestions/bugs that you find are welcome.

I’ll be creating soon some documentation on it. I’ll do it in two ways:

+ The powershell way
+ The MarkDown way

For now I’ll just leave the link to the script here. Sorry for the Portuguese names inside the scripts.

A resume of what it does:

+ Estimates number of members in each dimension attribute
+ Estimates number of rows in each existing partitions
+ Redesigns/creates Aggregations for each measure group
+ Recreates partitions based on Measure Group’s custom properties (in annotations)

Limitations:

+ Only tested on SQL Server Data sources
+ ...

Requirements:

+ AMO installed
+ SSAS 2005 + Database
+ Powershell :P

Download here: DO-SSASDBPerfMaintenace.ps1

*skullkiller*

[include](includes/plagiarism.md)

<script>
var idcomments_acct = '857a4a7d40b5baf6e007159d3686e3fe';
var idcomments_post_id;
var idcomments_post_url;
</script>
<span id="IDCommentsPostTitle" style="display:none"></span>
<script type='text/javascript' src='http://www.intensedebate.com/js/genericCommentWrapperV2.js'></script>