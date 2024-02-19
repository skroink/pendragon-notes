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
            nodes:  [{"id":1,"photo":"../../images/Isolde of Ravenshaw.jpg","name":"Isolde of Ravenshaw","pids":[2],"gender":"female","house":"House Ravenshaw","status":"Alive"},{"id":2,"photo":"../../images/Geraint ap Gwilym.jpg","name":"Geraint ap Gwilym","pids":[1],"gender":"male","house":"House Dolforwyn","status":"Alive"}]
		})
	}
}
</script>