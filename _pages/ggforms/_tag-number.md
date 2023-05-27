## Number
Adding `#number` to the description will convert a short-answer text question into a number keypad.

Additional tags:
1. `#minValue` (optional, default is no restriction)
<br/>Specify the minimum valid value. Invalid values will not be accepted.
1. `#maxValue` (optional, default is no restriction)
<br/>Specify the maximum valid value. Invalid values will not be accepted.
1. `#decimals` (optional, default is no restriction)
<br/>Specify the maximum number of decimals allowed.
1. `constraintMessage` (optional)
<br/>Custom message to display if the value is not between minValue and maxValue.

### Example
<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_number_1.png" /></td>
</tr>
</table>

<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_number_2.png" /></td>
<td><img src="{{ site.baseurl }}/assets/img/q_number_3.png" /></td>
<td><img src="{{ site.baseurl }}/assets/img/q_number_4.png" /></td>
</tr>
</table>

