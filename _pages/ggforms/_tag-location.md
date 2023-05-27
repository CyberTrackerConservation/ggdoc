## Location
Adding `#geopoint` to the description will convert a short-answer text question into a GPS location question.

Additional tags:
1. `#fixCount` (default `4`)
<br/>This is the number of warmup readings to take. GPS devices may produce inaccurate readings until they have warmed up. 
1. `#snapOnSave` (default `no`)
<br/>If this tag is set to `yes`, then the question will be automatically taken when the user presses the save button. Otherwise, the location is asked like a normal question.
1. `#allowManual` (default `yes`)
<br/>If this tag is set to `yes`, then the reading can be customized by the user by entering it manually. Otherwise, the reading can only come from the GPS. 

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



