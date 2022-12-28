# SongQuizV3

## Not Working For All Songs
### Spotify Search API doesn't always return the correct title and artist if you input the youtube title of the song (youtube title is formatted way differently than the spotify one so it has trouble searching) . Sometimes it returns a remix version and the artist is listed as someone else.
### I would fix it but it would require parsing the json file and retrieving the data which would require some manual input which isn't what I wanted in this 
### project. 

### TL;DR Spotify Search API kinda sucks sometimes 



## Requirements: 
<div><h3>1. <a href="https://app.tango.us/app/workflow/ee6c2aac-b760-40ab-af68-3995da4e8e4a?recording=true" target="_blank">Go to https://developer.spotify.com/dashboard/applications</a> and create a Spotify Web App</h3>
</div>

<div><h3>2. Copy your Client ID</h3>
<img src="https://images.tango.us/workflows/ee6c2aac-b760-40ab-af68-3995da4e8e4a/steps/b28d14e6-fa41-4d30-8bd7-4868bef7eef3/fb50af05-4e87-42a0-9e28-20bdce37b24d.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.0599&fp-y=0.3529&fp-z=2.8402&w=1200&mark-w=0.2&mark-pad=0&mark64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmsucG5n&ar=1920%3A969" width="600" alt="Copy your Client ID" />
</div>

<div><h3>3. Copy your Client Secret</h3>
<img src="https://images.tango.us/workflows/ee6c2aac-b760-40ab-af68-3995da4e8e4a/steps/ed6542a3-d3bc-4662-bb3f-c270d6112626/c9e6a133-1109-4bf1-b3ef-811c3ea10511.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.0833&fp-y=0.3911&fp-z=2.5065&w=1200&mark-w=0.2&mark-pad=0&mark64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmsucG5n&ar=1920%3A969" width="600" alt="Copy your Client Secret" />
</div>

<div><h3>4. Click on ❁ EDIT SETTINGS</h3>
<img src="https://images.tango.us/workflows/ee6c2aac-b760-40ab-af68-3995da4e8e4a/steps/555d2564-81dd-4b22-a77b-da3dba3edd99/ee0ee6b6-76c8-4747-a8f4-7e336509aff3.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.6922&fp-y=0.1765&fp-z=2.7866&w=1200&mark-w=0.2&mark-pad=0&mark64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmsucG5n&ar=1920%3A969" width="600" alt="Click on ❁ EDIT SETTINGS" />
</div>

<div><h3>5. Paste "https://zaramen.github.io/SongQuiz/" into Redirect URIs</h3>
<img src="https://images.tango.us/workflows/ee6c2aac-b760-40ab-af68-3995da4e8e4a/steps/3c423c1c-fafd-4b1d-b3ca-1443071993ac/551c7d4b-1405-4209-9773-c0b12fdf63b6.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.4794&fp-y=0.6295&fp-z=1.9296&w=1200&mark-w=0.2&mark-pad=0&mark64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmsucG5n&ar=1920%3A969" width="600" alt="Paste &quot;https://zaramen.github.io/SongQuiz/&quot; into Redirect URIs" />
</div>

<div><h3>6. Click on ADD</h3>
</div>

<div><h3>7. Click on SAVE</h3>
<img src="https://images.tango.us/workflows/ee6c2aac-b760-40ab-af68-3995da4e8e4a/steps/2ac8cd21-819c-4f07-aac4-1eee32977dae/a7e1a390-6908-48ae-8329-8d8ecccf5af8.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.3969&fp-y=0.8793&fp-z=2.8319&w=1200&mark-w=0.2&mark-pad=0&mark64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmsucG5n&ar=1920%3A969" width="600" alt="Click on SAVE" />
</div>

<hr/>

