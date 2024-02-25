---
hide:
  - toc
---
| name                                                                         |
| ---------------------------------------------------------------------------- |
| [[Characters/House Ravenshaw/Isolde of Ravenshaw.md\|Isolde of Ravenshaw]]   |
| [[Characters/House Ravenshaw/Caradoc of Ravenshaw.md\|Caradoc of Ravenshaw]] |


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
            nodes:  [{"id":1,"photo":"../../images/Geraint ap Gwilym.jpg","name":"Geraint ap Gwilym","birth":"460","pids":[2],"gender":"male","house":"House Dolforwyn","status":"Alive"},{"id":2,"photo":"../../images/Isolde of Ravenshaw.jpg","name":"Isolde of Ravenshaw","birth":"462","pids":[1],"gender":"female","house":"House Ravenshaw","status":"Alive"},{"id":3,"photo":"../../images/Caradoc of Ravenshaw.jpg","name":"Caradoc of Ravenshaw","birth":"845","pids":[],"gender":"male","house":"House Ravenshaw","status":"Alive"}]
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
			
			if (cnodeData.engaged != undefined && nodeData.engaged != undefined && cnodeData.engaged.includes(args.node.id) && nodeData.engaged.includes(args.cnode.id)) {

				args.html = args.html
					.replace("path", "path stroke-dasharray='5, 2'");
					
				args.html = args.html
					.replace(/stroke=\"*\"/g, "stroke='#049ae5'");
			}
		});
	}
}

</script>