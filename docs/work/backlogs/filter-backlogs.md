---
title: Filter backlogs  
description: Filter your backlog based on keywords, tags, or other fields   
ms.technology: vs-devops-wit
ms.prod: vs-devops-alm
ms.assetid: 
ms.manager: douge
ms.author: kaelli
ms.date: 10/06/2017
---
  

# Filter backlogs or queries

[!INCLUDE [temp](../_shared/version-vsts-tfs-all-versions.md)] 

<!--- NEEDS UPDATING BASED ON FEATURES UNDER RELEASE  --> 
<a id="filter"></a>
 
If you have many items listed in your product or portfolio backlog&mdash;and you want to focus on a subset of them&mdash;you can filter the set. 


## Filter based on keywords or fields (VSTS)    

> [!NOTE]   
> **Feature availability**: The ability to filter your backlog or a query based on the Work Item Type, Assigned To, or State fields is available from VSTS. For queries, you must enable the [New Queries Experience](../track/queries-preview.md). 

You can filter work items by typing a keyword or using one or more of the fields provided, such as work item type, assigned to, state, and tags. Based on the keyword that you enter, the filter function will list work items based on any visible/displayed column or field, including tags. Also, you can enter a value for an ID, whether or not the ID field is visible.  

<img src="_img/filter-backlogs-options.png" alt="Backlogs, turn filtering on" style="border: 2px solid #C3C3C3;" />

The filtered set is always a flat list, even if you've selected to show parents. 


## Filter based on keywords (TFS) 

You can use keywords to filter your backlogs or queries. The filter function lists those work items based on any visible/displayed column or field, including tags, based on the keyword that you enter. Also, you can enter a value for an ID, whether or not the ID field is visible.  

Here, we filter the backlog to only show items that include 'Web' in any one of the displayed column fields. 

<img src="_img/cyb-filter-backlog.png" alt="Apply text filter" style="border: 2px solid #C3C3C3;" />  

The filtered set is always a flat list, even if you've selected to show parents.  


## Filter based on tags (TFS) 
If you've [added tags to your work items](../track/add-tags-to-work-items.md), you can filter your backlogs, Kanban boards, and query results using the ![tag filter icon](../_img/icons/tag_filter_icon.png) tag filter. For backlogs and query results, add Tags as a column option prior to filtering on tags.  

To learn more about filtering using tags, see [Add tags to work items to categorize and filter lists and boards, Filter lists using tags](../track/add-tags-to-work-items.md#filter)
 

## Related notes  
- [Tags](../track/add-tags-to-work-items.md) 
- [Set column options](set-column-options.md)  


### Characters ignored by filter criteria

The filter criteria ignores the following characters when the field value starts with the character: ```{, (, [, !, @, #, $, %, ^, &, *, ~, `, ', "```.  
