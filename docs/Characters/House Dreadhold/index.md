---
hide:
  - navigation
---
| name                                                                               |
| ---------------------------------------------------------------------------------- |
| [[Characters/House Dreadhold/Penellaphe of Dreadhold.md\|Penellaphe of Dreadhold]] |


<div style="width:700px; height:700px;" id="tree"></div>

<script>
  document.onreadystatechange = function () {
     if (document.readyState == "complete") {
     	  let family = new FamilyTree(document.getElementById("tree"), {
            nodeBinding: {field_0: "name",field_1: "title",field_2: "house",img_0: "photo" },
            siblingSpread: 150,
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
            nodes:  [{"id":1,"photo":"../../images/Penellaphe of Dreadhold.jpg","name":"Penellaphe of Dreadhold","pids":[],"gender":"female","house":"House Dreadhold","status":"Alive"}]
		})
	}
}
</script>