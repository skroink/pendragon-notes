| name                                                              |
| ----------------------------------------------------------------- |
| [[Characters/House Tirion/Elinor of Tirion.md\|Elinor of Tirion]] |


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
            roots: [1],
            filterBy: {
	            gender: {},
	            house: {} ,
	            status: {
		            Deceased: { checked:false }
	            }
            },
            nodes:  [{"id":1,"photo":"../../images/Madoc ap Gwilym.jpg","name":"Madoc ap Gwilym","birth":"465","pids":[2],"gender":"male","house":"House Dolforwyn","status":"Alive"},{"id":2,"photo":"../../images/Elinor of Tirion.jpg","name":"Elinor of Tirion","birth":"467","pids":[1],"gender":"female","house":"House Tirion","status":"Alive"}]
		})


		
		family.on('render-link', function (sender, args) {
			var cnodeData = family.get(args.cnode.id);
			var nodeData = family.get(args.node.id);

			if (cnodeData.divorced != undefined && nodeData.divorced != undefined && cnodeData.divorced.includes(args.node.id) && nodeData.divorced.includes(args.cnode.id)) {

				args.html = args.html
					.replace("path", "path stroke-dasharray='3, 2'");
					
				args.html = args.html
					.replace(/stroke=\"*\"/g, "stroke='#AA1945'");
			}
		});
	}
}

</script>