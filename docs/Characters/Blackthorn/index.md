---
hide:
  - toc
---

<div style="width:100%; height:700px;" id="tree"></div>

<script>
  document.onreadystatechange = function () {
     if (document.readyState == "complete") {
     	  let family = new FamilyTree(document.getElementById("tree"), {
            nodeBinding: {field_0: "name",field_1: "title",field_2: "house",img_0: "photo" },
            levelSeparation: 100,
            siblingSeparation: 100,
            subtreeSeparation:150,
            template: "john",
            editForm: {
            photoBinding: "photo",
            buttons: null
            },
            filterBy: {
	            gender: {},
	            house: {} ,
	            status: {
		            Deceased: { checked:false }
	            }
            },
            nodes:  [{"id":1,"photo":"../../images/Rhys of Blackthorn.jpg","name":"Rhys of Blackthorn","pids":[2],"gender":"male","house":"Blackthorn","status":"Alive"},{"id":2,"photo":"../../images/Maelona ferch Eilwen.jpg","name":"Maelona ferch Eilwen","pids":[1],"gender":"female","house":"House Dolforwyn","status":"Alive"}]
		})
	}
}
</script>