---
hide:
  - toc
---
| name                                                                               |
| ---------------------------------------------------------------------------------- |
| [[Characters/House Dreadhold/Penellaphe of Dreadhold.md\|Penellaphe of Dreadhold]] |


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
            nodes:  [{"id":1,"photo":"../../images/Penellaphe of Dreadhold.jpg","name":"Penellaphe of Dreadhold","birth":"465","pids":[],"gender":"female","house":"House Dreadhold","status":"Alive"}]
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