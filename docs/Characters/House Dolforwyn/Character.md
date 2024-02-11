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
            nodes:  [{"id":"Seren ferch Arianwen.md","name":"Seren ferch Arianwen","mId":"Arianwen ferch Cerdic.md","fId":"Bran ap Cynric.md"},{"id":"Madoc ap Gwilym.md","name":"Madoc ap Gwilym","mId":"Eilwen ferch Ealdred.md","fId":"Gwilym ap Cynric.md"},{"id":"Llywelyn ap Emrys.md","name":"Llywelyn ap Emrys","mId":"Eira ferch Gwyn.md","fId":"Emrys ap Bran.md"},{"id":"Gwenhwyfar ferch Eira.md","name":"Gwenhwyfar ferch Eira","mId":"Eira ferch Gwyn.md","fId":"Emrys ap Bran.md"},{"id":"Bran ap Cynric.md","name":"Bran ap Cynric","mId":"Branwen of Boudica.md","fId":"Cynric ap Gwilym.md"}]</script>