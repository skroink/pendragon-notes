---
hide:
  - toc
---
| name                                                                          |
| ----------------------------------------------------------------------------- |
| [[Characters/House Daelwood/Arianwen ferch Cerdic.md\|Arianwen ferch Cerdic]] |


<div style="width:100%; height:700px;" id="tree"></div>

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
            nodes:  [{"id":1,"photo":"../../images/Arianwen ferch Cerdic.jpg","name":"Arianwen ferch Cerdic","pids":[],"gender":"female","house":"House Daelwood","status":"Alive"}]
		})
	}
}
</script>