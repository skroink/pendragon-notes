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
  "name": "Eilwen ferch Ealdred",
  "pids": [
   5
  ],
  "gender": "male"
 },
 {
  "id": 1,
  "name": "Seren ferch Arianwen",
  "pids": [],
  "gender": "female",
  "mid": 13,
  "fid": 12
 },
 {
  "id": 2,
  "name": "Maelona ferch Eilwen",
  "pids": [],
  "gender": "female",
  "mid": 0,
  "fid": 5
 },
 {
  "id": 3,
  "name": "Madoc ap Gwilym",
  "pids": [],
  "gender": "male",
  "mid": 0,
  "fid": 5
 },
 {
  "id": 4,
  "name": "Llywelyn ap Emrys",
  "pids": [],
  "gender": "female",
  "fid": 8
 },
 {
  "id": 5,
  "name": "Gwilym ap Cynric",
  "pids": [],
  "gender": "male",
  "mid": 11,
  "fid": 10
 },
 {
  "id": 6,
  "name": "Gwenhwyfar ferch Eira",
  "pids": [],
  "gender": "female",
  "fid": 8
 },
 {
  "id": 7,
  "name": "Geraint ap Gwilym",
  "pids": [],
  "gender": "male",
  "mid": 0,
  "fid": 5
 },
 {
  "id": 8,
  "name": "Emrys ap Bran",
  "pids": [],
  "gender": "male",
  "mid": 13,
  "fid": 12
 },
 {
  "id": 9,
  "name": "Elowen ferch Branwen",
  "pids": [],
  "gender": "female",
  "mid": 11,
  "fid": 10
 },
 {
  "id": 10,
  "name": "Cynric ap Gwilym",
  "pids": [
   11
  ],
  "gender": "male"
 },
 {
  "id": 11,
  "name": "Branwen of Boudica",
  "pids": [
   10
  ],
  "gender": "female"
 },
 {
  "id": 12,
  "name": "Bran ap Cynric",
  "pids": [
   13
  ],
  "gender": "male",
  "mid": 11,
  "fid": 10
 },
 {
  "id": 13,
  "name": "Arianwen ferch Cerdic",
  "pids": [
   12
  ],
  "gender": "female"
 }
]
		})
	}
}
</script>