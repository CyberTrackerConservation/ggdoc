## Photos
Adding `#photo` to the description will convert a short-answer text question into a photo question.

{: .important }
>
> Using `#photo` requires that the `#fileFolder` tag is specified in the form description. Follow the one-time setup instructions [here]({{ site.baseurl }}/file-upload/).
>

Additional tags:
1. `#maxPixels` (default is `2048`)
This is the maximum width of the image. If the camera takes larger images, they will be resized such that the longest edge matches this value. 
1. `#minCount` (default is `0`)
This tag indicates the minimum number of images that are required. The default is `0` meaning that the question is optional.
1. `#maxCount` (default is `1`)
This tag indicates the maximum number of images that can be captured. If more than 1, then a grid of photos is created. 

### Example 1
In this example, the question specifies a single photo.
<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_photo_0.png" /></td>
</tr>
</table>

<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_photo_1.png" /></td>
<td><img src="{{ site.baseurl }}/assets/img/q_photo_2.png" /></td>
<td><img src="{{ site.baseurl }}/assets/img/q_photo_3.png" /></td>
</tr>
</table>

### Example 2
In this example, the question specifies at most 5 photos and they should be size-reduced so that they are no more than 1600 pixels on a side.
<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_photo_7.png" /></td>
</tr>
</table>

<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_photo_4.png" /></td>
<td><img src="{{ site.baseurl }}/assets/img/q_photo_5.png" /></td>
<td><img src="{{ site.baseurl }}/assets/img/q_photo_6.png" /></td>
</tr>
</table>

