# astralife-frontend-ionic-angular
<h1>How to run</h1>
<ul>
  <li>Create an Ionic Application</li>
  <li>ionic start astralife blank --type=angular</li>
</ul>
<ul>
  <li>Add New Pages in Application</li>
  <li>
     ionic generate page employees-create<br>
     ionic generate page employees-edit<br>
     ionic generate page employees-list<br>
     ionic generate page employees-detail
  </li>
  <li>atau copy semua resource di atas </li>
</ul>
<ul>
  <li>Edit dan Sesuaikan base_path</li>
  <li>dir => src -> app -> services -> api.service.ts</li>
</ul>
<ul>
  <li>Run App</li>
  <li>ionic serve --open</li>
</ul>

<h1>FULL External link download</h1>
<a href="http://202.157.184.81/download/astraLife.zip">DOWNLOAD FULL</a>
<br>
<br>
note :
jika terkena blocked by CORS policy<br>
"Access to XMLHttpRequest at 'http://localhost:8080/employee' from origin 'http://localhost:8100' has been blocked by CORS policy: No 'Access-Control-Allow-Origin' header is present on the requested resource."<br><br>

bisa mencoba api server data.json local dengan cara mendownload file <a href="http://202.157.184.81/download/astraLife.zip">link</a> berikut dan rubah "base_path = 'http://localhost:3000/employees';" kemudian run "json-server --watch API/data.json"<br>

<h1>Terimakasih</h1>
