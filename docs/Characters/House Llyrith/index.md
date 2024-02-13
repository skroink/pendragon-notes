---
hide:
  - navigation
---
| name                                                                       |
| -------------------------------------------------------------------------- |
| [[Characters/House Llyrith/Eilwen ferch Ealdred.md\|Eilwen ferch Ealdred]] |


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
            nodes:  [{"id":1,"photo":"../../images/Eilwen ferch Ealdred.jpg","name":"Eilwen ferch Ealdred","pids":[2],"gender":"female","house":"House Llyrith","status":"Alive"},{"id":2,"photo":"../../images/Gwilym ap Cynric.jpg","name":"Gwilym ap Cynric","pids":[1],"gender":"male","house":"House Dolforwyn","status":"Alive"}]
		})
	}
}
</script>