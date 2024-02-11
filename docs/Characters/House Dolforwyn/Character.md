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
            nodes:  [{"id":0,"name":"Eira ferch Gwyn"},{"id":1,"name":"Eilwen ferch Ealdred"},{"id":2,"name":"Seren ferch Arianwen","mid":15,"fid":14},{"id":3,"name":"Maelona ferch Eilwen"},{"id":4,"name":"Madoc ap Gwilym","mid":1,"fid":6},{"id":5,"name":"Llywelyn ap Emrys","mid":0,"fid":9},{"id":6,"name":"Gwilym ap Cynric"},{"id":7,"name":"Gwenhwyfar ferch Eira","mid":0,"fid":9},{"id":8,"name":"Geraint ap Gwilym"},{"id":9,"name":"Emrys ap Bran"},{"id":10,"name":"Elowen ferch Branwen"},{"id":11,"name":"Character"},{"id":12,"name":"Cynric ap Gwilym"},{"id":13,"name":"Branwen of Boudica"},{"id":14,"name":"Bran ap Cynric","mid":13,"fid":12},{"id":15,"name":"Arianwen ferch Cerdic"}]
		})
	}
}
</script>