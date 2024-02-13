---
hide:
  - navigation
---
| name                                                               |
| ------------------------------------------------------------------ |
| [[Characters/House Snowridge/Eira ferch Gwyn.md\|Eira ferch Gwyn]] |


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
            nodes:  [{"id":1,"photo":"../../images/Eira ferch Gwyn.jpg","name":"Eira ferch Gwyn","pids":[2],"gender":"female","house":"House Snowridge","status":"Alive"},{"id":2,"photo":"../../images/Emrys ap Bran.jpg","name":"Emrys ap Bran","pids":[1],"gender":"male","house":"House Dolforwyn","status":"Alive"}]
		})
	}
}
</script>