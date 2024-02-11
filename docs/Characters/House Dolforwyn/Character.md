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
            nodes: [
	             <p><span><p>[{"id":"Characters/House Dolforwyn/Bran ap Cynric.md","mid":"Characters/House Dolforwyn/Branwen of Boudica.md","fid":"Characters/House Dolforwyn/Cynric ap Gwilym.md","gender":"male"},{"id":"Characters/House Dolforwyn/Gwenhwyfar ferch Eira.md","mid":"Characters/House Snowridge/Eira ferch Gwyn.md","fid":"Characters/House Dolforwyn/Emrys ap Bran.md","gender":"female"},{"id":"Characters/House Dolforwyn/Llywelyn ap Emrys.md","mid":"Characters/House Snowridge/Eira ferch Gwyn.md","fid":"Characters/House Dolforwyn/Emrys ap Bran.md","gender":"female"},{"id":"Characters/House Dolforwyn/Madoc ap Gwilym.md","mid":"Characters/House Llyrith/Eilwen ferch Ealdred.md","fid":"Characters/House Dolforwyn/Gwilym ap Cynric.md","gender":"male"},{"id":"Characters/House Dolforwyn/Seren ferch Arianwen.md","mid":"Characters/House Daelwood/Arianwen ferch Cerdic.md","fid":"Characters/House Dolforwyn/Bran ap Cynric.md","gender":"female"}]</p></span></p>
            ]
        });
   }
}	
</script>