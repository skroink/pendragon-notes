---
test: true
---
<div style="width:100%; height:700px;" id="tree"></div>

<script>
  document.onreadystatechange = function () {
     if (document.readyState == "complete") {
     	  let family = new FamilyTree(document.getElementById("tree"), {
            nodeBinding: {
                field_0: "name",
                img_0: "photo"
            },
            nodes:  [
 {
  "id": 0,
  "photo": "https://skroink.github.io/pendragon-notes/images/Eilwen ferch Ealdred.png",
  "name": "Eilwen ferch Ealdred",
  "pids": [
   5
  ],
  "gender": "male"
 },
 {
  "id": 1,
  "photo": "https://skroink.github.io/pendragon-notes/images/Seren ferch Arianwen.png",
  "name": "Seren ferch Arianwen",
  "pids": [],
  "gender": "female",
  "mid": 13,
  "fid": 12
 },
 {
  "id": 2,
  "photo": "https://skroink.github.io/pendragon-notes/images/Maelona ferch Eilwen.png",
  "name": "Maelona ferch Eilwen",
  "pids": [],
  "gender": "female",
  "mid": 0,
  "fid": 5
 },
 {
  "id": 3,
  "photo": "https://skroink.github.io/pendragon-notes/images/Madoc ap Gwilym.png",
  "name": "Madoc ap Gwilym",
  "pids": [],
  "gender": "male",
  "mid": 0,
  "fid": 5
 },
 {
  "id": 4,
  "photo": "https://skroink.github.io/pendragon-notes/images/Llywelyn ap Emrys.png",
  "name": "Llywelyn ap Emrys",
  "pids": [],
  "gender": "female",
  "fid": 8
 },
 {
  "id": 5,
  "photo": "https://skroink.github.io/pendragon-notes/images/Gwilym ap Cynric.png",
  "name": "Gwilym ap Cynric",
  "pids": [],
  "gender": "male",
  "mid": 11,
  "fid": 10
 },
 {
  "id": 6,
  "photo": "https://skroink.github.io/pendragon-notes/images/Gwenhwyfar ferch Eira.png",
  "name": "Gwenhwyfar ferch Eira",
  "pids": [],
  "gender": "female",
  "fid": 8
 },
 {
  "id": 7,
  "photo": "https://skroink.github.io/pendragon-notes/images/Geraint ap Gwilym.png",
  "name": "Geraint ap Gwilym",
  "pids": [],
  "gender": "male",
  "mid": 0,
  "fid": 5
 },
 {
  "id": 8,
  "photo": "https://skroink.github.io/pendragon-notes/images/Emrys ap Bran.png",
  "name": "Emrys ap Bran",
  "pids": [],
  "gender": "male",
  "mid": 13,
  "fid": 12
 },
 {
  "id": 9,
  "photo": "https://skroink.github.io/pendragon-notes/images/Elowen ferch Branwen.png",
  "name": "Elowen ferch Branwen",
  "pids": [],
  "gender": "female",
  "mid": 11,
  "fid": 10
 },
 {
  "id": 10,
  "photo": "https://skroink.github.io/pendragon-notes/images/Cynric ap Gwilym.png",
  "name": "Cynric ap Gwilym",
  "pids": [
   11
  ],
  "gender": "male"
 },
 {
  "id": 11,
  "photo": "https://skroink.github.io/pendragon-notes/images/Branwen of Boudica.png",
  "name": "Branwen of Boudica",
  "pids": [
   10
  ],
  "gender": "female"
 },
 {
  "id": 12,
  "photo": "https://skroink.github.io/pendragon-notes/images/Bran ap Cynric.png",
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
  "photo": "https://skroink.github.io/pendragon-notes/images/Arianwen ferch Cerdic.png",
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