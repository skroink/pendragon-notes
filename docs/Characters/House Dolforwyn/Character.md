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
                { id: 1, pids: [2], name: "Amber McKenzie", gender: "female" },
                { id: 2, pids: [1], name: "Ava Field", gender: "male" },
                { id: 3, mid: 1, fid: 2, name: "Peter Stevens", gender: "male" }  
            ]
        });
   }
}	
</script>