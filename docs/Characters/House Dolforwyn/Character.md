---
test: true
---
<div style="width:100%; height:700px;" id="tree"></div>

<script>
  document.onreadystatechange = function () {
     if (document.readyState == "complete") {
     	  let family = new FamilyTree(document.getElementById("tree"), {
            nodeBinding: {
                field_0: "name"
            },
            nodes:  [
 {
  "id": 0,
  "name": "Seren ferch Arianwen",
  "pids": [],
  "gender": "female",
  "fid": 11
 },
 {
  "id": 1,
  "name": "Maelona ferch Eilwen",
  "pids": [],
  "gender": "female",
  "fid": 4
 },
 {
  "id": 2,
  "name": "Madoc ap Gwilym",
  "pids": [],
  "gender": "male",
  "fid": 4
 },
 {
  "id": 3,
  "name": "Llywelyn ap Emrys",
  "pids": [],
  "gender": "female",
  "fid": 7
 },
 {
  "id": 4,
  "name": "Gwilym ap Cynric",
  "pids": [
   4
  ],
  "gender": "male",
  "mid": 10,
  "fid": 9
 },
 {
  "id": 5,
  "name": "Gwenhwyfar ferch Eira",
  "pids": [],
  "gender": "female",
  "fid": 7
 },
 {
  "id": 6,
  "name": "Geraint ap Gwilym",
  "pids": [],
  "gender": "male",
  "fid": 4
 },
 {
  "id": 7,
  "name": "Emrys ap Bran",
  "pids": [],
  "gender": "male",
  "fid": 11
 },
 {
  "id": 8,
  "name": "Elowen ferch Branwen",
  "pids": [],
  "gender": "female",
  "mid": 10,
  "fid": 9
 },
 {
  "id": 9,
  "name": "Cynric ap Gwilym",
  "pids": [
   10
  ],
  "gender": "male"
 },
 {
  "id": 10,
  "name": "Branwen of Boudica",
  "pids": [
   9
  ],
  "gender": "female"
 },
 {
  "id": 11,
  "name": "Bran ap Cynric",
  "pids": [],
  "gender": "male",
  "mid": 10,
  "fid": 9
 }
]
		})
	}
}
</script>