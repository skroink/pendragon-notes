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
            nodes:  [{"id":"Eira ferch Gwyn.md","name":"Eira ferch Gwyn"},{"id":"Eilwen ferch Ealdred.md","name":"Eilwen ferch Ealdred"},{"id":"Seren ferch Arianwen.md","name":"Seren ferch Arianwen","mid":"Arianwen ferch Cerdic.md","fid":"Bran ap Cynric.md"},{"id":"Maelona ferch Eilwen.md","name":"Maelona ferch Eilwen"},{"id":"Madoc ap Gwilym.md","name":"Madoc ap Gwilym","mid":"Eilwen ferch Ealdred.md","fid":"Gwilym ap Cynric.md"},{"id":"Llywelyn ap Emrys.md","name":"Llywelyn ap Emrys","mid":"Eira ferch Gwyn.md","fid":"Emrys ap Bran.md"},{"id":"Gwilym ap Cynric.md","name":"Gwilym ap Cynric"},{"id":"Gwenhwyfar ferch Eira.md","name":"Gwenhwyfar ferch Eira","mid":"Eira ferch Gwyn.md","fid":"Emrys ap Bran.md"},{"id":"Geraint ap Gwilym.md","name":"Geraint ap Gwilym"},{"id":"Emrys ap Bran.md","name":"Emrys ap Bran"},{"id":"Elowen ferch Branwen.md","name":"Elowen ferch Branwen"},{"id":"Character.md","name":"Character"},{"id":"Cynric ap Gwilym.md","name":"Cynric ap Gwilym"},{"id":"Branwen of Boudica.md","name":"Branwen of Boudica"},{"id":"Bran ap Cynric.md","name":"Bran ap Cynric","mid":"Branwen of Boudica.md","fid":"Cynric ap Gwilym.md"},{"id":"Arianwen ferch Cerdic.md","name":"Arianwen ferch Cerdic"}]		})
	}
}
</script>