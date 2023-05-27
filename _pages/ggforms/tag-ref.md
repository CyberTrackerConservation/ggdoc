---
layout: page
title: Tag reference
nav_order: 2000
permalink: /tags/
has_children: true
has_toc: false
---
# Tag reference

Rilla extends Google Forms™ with new features. This is done by adding a **tag** to the _Description_ property of a question. For example, if you add `#geopoint` to a short text question, then it will become a question which captures a location from the GPS.

Tags always start with a `#` on a new line at the **bottom** of the question description property. The description can still be used for adding help to a question and Rilla will remove tags so they will not appear in the description text.

## Example
### 1. Enable question description
Enable the description property for a question by using the options dropdown and selecting **Description**:
<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_tags.png" /></td>
</tr>
</table>

### 2. Add `#geopoint` to the end of the description
After adding a helpful text description, add `#geopoint` on a new line at the bottom:
<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_tags_0.png" /></td>
</tr>
</table>

### 3. Enter data
Capture data and note that the question asks for a GPS location:
<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_tags_1.png" /></td>
<td><img src="{{ site.baseurl }}/assets/img/q_tags_2.png" /></td>
<td><img src="{{ site.baseurl }}/assets/img/q_tags_3.png" /></td>
</tr>
</table>

### 4. View location in spreadsheet
Back in your browswer, open the linked spreadsheet to see the location - the format is `latitude longitude`:
<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_tags_4.png" /></td>
</tr>
</table>
