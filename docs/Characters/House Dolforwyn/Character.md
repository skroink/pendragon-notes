---
Birth: "[[440]]"
test: true
Children:
  - "[[Eira ferch Gwyn|Eira ferch Gwyn]]"
  - "[[Eilwen ferch Ealdred|Eilwen ferch Ealdred]]"
Siblings:
  - "[[Eira ferch Gwyn|Eira ferch Gwyn]]"
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
  "gender": "female",
  "fid": 11
 },
 {
  "id": 1,
  "name": "Maelona ferch Eilwen",
  "gender": "female",
  "fid": 4
 },
 {
  "id": 2,
  "name": "Madoc ap Gwilym",
  "gender": "male",
  "fid": 4
 },
 {
  "id": 3,
  "name": "Llywelyn ap Emrys",
  "gender": "female",
  "fid": 7
 },
 {
  "id": 4,
  "name": "Gwilym ap Cynric",
  "gender": "male",
  "mid": 10,
  "fid": 9
 },
 {
  "id": 5,
  "name": "Gwenhwyfar ferch Eira",
  "gender": "female",
  "fid": 7
 },
 {
  "id": 6,
  "name": "Geraint ap Gwilym",
  "gender": "male",
  "fid": 4
 },
 {
  "id": 7,
  "name": "Emrys ap Bran",
  "gender": "male",
  "fid": 11
 },
 {
  "id": 8,
  "name": "Elowen ferch Branwen",
  "gender": "female",
  "mid": 10,
  "fid": 9
 },
 {
  "id": 9,
  "name": "Cynric ap Gwilym",
  "gender": "male"
 },
 {
  "id": 10,
  "name": "Branwen of Boudica",
  "gender": "female"
 },
 {
  "id": 11,
  "name": "Bran ap Cynric",
  "gender": "male",
  "mid": 10,
  "fid": 9
 }
]
		})
	}
}
</script>