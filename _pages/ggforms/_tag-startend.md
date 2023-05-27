## Start and End time
Using `#start` or `#end` will convert a short-answer text question into a hidden question, which captures data about the observation.

**Start** is the time when the observation was created (using the `+` button in the lower right corner of the screen). 

**End** is the time when the user pressed the save button. If a sighting is edited, then the end time is updated.

{: .important }
>
> Using `#start` or `#end` will mark the question as hidden. This means it will show up in the data, but the user will not be asked the question.
>

### Example
<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_startend_1.png" /></td>
</tr>
</table>

<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_startend_2.png" /></td>
</tr>
</table>

{: .note }
> 1. Start and end times use [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) as their format. This is the local time + time zone offset.
> 1. `Timestamp` column is the time when the observation was uploaded. 


