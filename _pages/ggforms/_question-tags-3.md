## Location
Use the `#geopoint` will convert the current short answer text question into a GPS location question.

This tag supports two additional sub-tags:
1. `#fixCount` (default is 4)
This is the number of readings to take before using the reading. This is useful, because many GPS devices produce inaccurate readings until they have warmed up. 
1. `#snapOnSave` (default is `no`)
If this tag is set to `yes`, then the question will be automatically taken when the user presses the save button.
1. `#allowManual` (default is `yes`)
If this tag is set to `yes`, then the reading can be customized by the user by entering it manually. Otherwise, the reading can only come from the GPS. 

### Example
<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_location_1.png" /></td>
</tr>
</table>

The format of the GPS coordinate is `latitude space longitude`:
<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_tags_4.png" /></td>
</tr>
</table>

The location is also visible on the field map:
<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_location_2.png" /></td>
<td><img src="{{ site.baseurl }}/assets/img/q_location_3.png" /></td>
<td><img src="{{ site.baseurl }}/assets/img/q_location_4.png" /></td>
</tr>
</table>



