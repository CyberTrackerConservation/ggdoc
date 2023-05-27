# File upload

In order to capture files (photos, audio, attachments), the form must contain a `#fileFolder` [tag]({{ site.baseurl }}/tags/) in the form description. This specifies the Google Drive™ folder where files will be uploaded to. 

## Instructions
1. Open your [Google Drive™](https://drive.google.com)
1. Create a new folder - the name does not matter, but it is recommended to call it something you will recognize later, e.g. `Rilla files`.
1. Right click on the folder and select `Share`
1. In the box labelled `Add people or groups`, add `ggforms@ggforms.iam.gserviceaccount.com`. This gives Rilla permission to upload files to this folder. This should only be done on the folder you want to add files to, do not add it to any other folder.
1. Click `Copy link` and then click `Share`
1. Return to your form and go to the form description box, just below the form title
1. Type `#fileFolder=` and then paste the link to your drive folder
1. Republish your form

<table>
<tr>
<td><img src="{{ site.baseurl }}/assets/img/q_file_upload_1.png" /></td>
</tr>
</table>

Check out the video to see it in action:
<iframe width="560" height="315" src="https://www.youtube.com/embed/YlisUgZjSx8" frameborder="0" allowfullscreen></iframe>
