---
layout: default
title: By Rules
parent: OneFilter AutoCAD User Guide
nav_order: 2
---

# OneFilter
{: .no_toc }
Quickly find your elements in AutoCAD models. Create conditions rules to filter objects and layers based on their properties and datas.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# By Rules

This tab is very similar to the Filters tab, but it allows you to apply rules sets and conditions to filters with "and" and "or".
The first step is to select whether you want to apply filters based on the Whole Model, the Current Selection or Active Space. Select the radio button to choose it.

![OneFilter filter model view](../../../../assets\images\OneFilter\OF-Br-FilterModel.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

## Rule Sets

Note that there is a Rule Set by created by default, so you can edit it, or create new Rule Sets.

1. Click on the New button to create a new Rule Set.

```yaml
# Note:
Double-click on the Rule Set to open the rename option.
```
![OneFilter new rule set](../../../../assets\images\OneFilter\OF-Br-NewRule.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

2. Select Rules and click on the Duplicate button to duplicate it.

![OneFilter duplicate rule](../../../../assets\images\OneFilter\OF-Br-Duplicate.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

3. Select Rules and click the Remove button to delete it.

![OneFilter remove rules](../../../../assets\images\OneFilter\OF-Br-Remove.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

```yaml
# Note:
Use the search box to search for Rule Sets.
```

---

## Definition

This tab allows you to create specific filter conditions for each rule. For this, select a rule from the table above to allow you to edit the filter settings.

1. Open the first drop-down list and choose Object Types.

2. Select the second drop-down list to choose the properties of the selected objetcs.

3. Choose the Condition to apply filter.

4. Enter a value or select a suggested value from the drop-down list.

Click on the Filter button to run the Condition Rule create.

![OneFilter Definition](../../../../assets\images\OneFilter\OF-Br-Definition.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

### Add condition

You can also apply more conditions to your rule. Click Add to insert a new definition into your rule, following the "AND/OR" condition.

```yaml
# Note:
Note that if you select the rule created and click Add, you will add a new definition as a child, thus creating a tree structure for your rule.
```
![OneFilter Add condition](../../../../assets\images\OneFilter\OF-Br-AddCondition.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

### Remove

Select the conditions created and click the Remove button to delete them.

![OneFilter Remove condition](../../../../assets\images\OneFilter\OF-Br-RemoveCondition.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

---

### Search

Use the search box to search for filtered elements in the main table.

![OneFilter search](../../../../assets\images\OneFilter\OF-Br-Search.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

### Select

Use the checkboxes to select the elements filtered and click on Select button to select it in the view.

![OneFilter select elements](../../../../assets\images\OneFilter\OF-Br-Select.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

### Isolate Object

Use the checkboxes to select the elements filtered and click on Isolate button to isolate it in the view.

![OneFilter isolate elements](../../../../assets\images\OneFilter\OF-Br-Isolate.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

```yaml
# Note:
Click End Isolation, or use the AutoCAD command "Unisolate" to return to the entire model view.
```

---

## Profile

Create profiles to save the rules and conditions created to filter the model in AutoCAD.

### Creating Profiles

OneFilter profiles make it easy to save your settings and reuse them later. It is also a handy way for BIM Managers to create standard rules (e.g., filename conventions) and share them across the organization.

Steps:
1. Click on the Profile drop-down list.
2. Click on Add New, and enter a Profile name.
3. Click to save the profile.

![OneFilter Creating profiles](../../../../assets\images\OneFilter\OF-Br-Profile.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

```
Tip for BIM Managers!  

Create the profiles in a network location to allow other users to import them.
See the "Importing Profiles" section to teach users how to pull profiles from a network location.
```

### Export Profile

OneFilter profiles make it easy to export profiles to stay compliant with your company standards (e.g., profiles in a network location).

1. Click on the Profile drop-down list and click to export.
2. Use the Windows File Explorer select a folter to save it (e.g., in a shared folder, location network, or local computer).
3. Click on the "Save" button to export the profile.

![OneFilter exporting profiles](../../../../assets\images\OneFilter\OF-Br-ExportProfile.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

### Importing Profiles

OneFilter profiles make it easy to import existing profiles to stay compliant with your company standards (e.g., profiles in a network location).

1. Click on the Profile drop-down list and click to import.
2. Use the Windows File Explorer to find the profile (e.g., in a shared folder, location network, or local computer)
3. Click on the "Open" button to import the profile.

![OneFilter importing profiles](../../../../assets\images\OneFilter\OF-Br-ImportProfile.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>

### Deleting Profiles

Steps:
1. Click on the Profile drop-down list.
2. Click on the Delete icon next to the profiles list.
3. Confirm.

![OneFilter deleting profiles](../../../../assets\images\OneFilter\OF-Br-DeleteProfile.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter-AutoCAD/DiRootsOne](https://diroots.com/autocad-plugins/dirootsone-for-autocad/).</sub>