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
            roots: [1],
            filterBy: {
	            gender: {},
	            house: {} ,
	            status: {
		            Deceased: { checked:false }
	            }
            },
            nodes:  [{"id":1,"photo":"../../images/Cynric ap Gwilym.jpg","name":"Cynric ap Gwilym","birth":"420","pids":[2],"gender":"male","house":"House Dolforwyn","status":"Deceased"},{"id":2,"photo":"../../images/Branwen of Boudica.jpg","name":"Branwen of Boudica","birth":"422","pids":[1],"gender":"female","house":"House Dolforwyn","status":"Alive"},{"id":3,"photo":"../../images/Arianwen ferch Cerdic.jpg","name":"Arianwen ferch Cerdic","birth":"439","pids":[4],"gender":"female","house":"House Daelwood","status":"Alive"},{"id":4,"photo":"../../images/Bran ap Cynric.jpg","name":"Bran ap Cynric","birth":"440","pids":[3],"gender":"male","mid":2,"fid":1,"house":"House Dolforwyn","status":"Alive"},{"id":5,"photo":"../../images/Gwilym ap Cynric.jpg","name":"Gwilym ap Cynric","birth":"442","pids":[6],"gender":"male","mid":2,"fid":1,"house":"House Dolforwyn","status":"Alive"},{"id":6,"photo":"../../images/Eilwen ferch Ealdred.jpg","name":"Eilwen ferch Ealdred","birth":"442","pids":[5],"gender":"female","house":"House Llyrith","status":"Alive"},{"id":7,"photo":"../../images/Elowen ferch Branwen.jpg","name":"Elowen ferch Branwen","birth":"447","pids":[],"gender":"female","mid":2,"fid":1,"house":"House Dolforwyn","status":"Deceased"},{"id":8,"photo":"../../images/Emrys ap Bran.jpg","name":"Emrys ap Bran","birth":"458","pids":[9],"gender":"male","mid":3,"fid":4,"house":"House Dolforwyn","status":"Alive"},{"id":9,"photo":"../../images/Eira ferch Gwyn.jpg","name":"Eira ferch Gwyn","birth":"459","pids":[8],"gender":"female","house":"House Snowridge","status":"Alive"},{"id":10,"photo":"../../images/Geraint ap Gwilym.jpg","name":"Geraint ap Gwilym","birth":"460","pids":[13],"gender":"male","mid":6,"fid":5,"house":"House Dolforwyn","status":"Alive"},{"id":11,"photo":"../../images/Seren ferch Arianwen.jpg","name":"Seren ferch Arianwen","birth":"462","pids":[],"gender":"female","mid":3,"fid":4,"house":"House Dolforwyn","status":"Alive"},{"id":12,"photo":"../../images/Rhys of Blackthorn.jpg","name":"Rhys of Blackthorn","birth":"462","pids":[14],"gender":"male","house":"Blackthorn","status":"Alive"},{"id":13,"photo":"../../images/Isolde of Ravenshaw.jpg","name":"Isolde of Ravenshaw","birth":"462","pids":[10],"gender":"female","house":"House Ravenshaw","status":"Alive"},{"id":14,"photo":"../../images/Maelona ferch Eilwen.jpg","name":"Maelona ferch Eilwen","birth":"463","pids":[12],"gender":"female","mid":6,"fid":5,"house":"House Dolforwyn","status":"Alive"},{"id":15,"photo":"../../images/Madoc ap Gwilym.jpg","name":"Madoc ap Gwilym","birth":"465","pids":[16],"gender":"male","mid":6,"fid":5,"house":"House Dolforwyn","status":"Alive"},{"id":16,"photo":"../../images/Elinor of Tirion.jpg","name":"Elinor of Tirion","birth":"467","pids":[15],"gender":"female","house":"House Tirion","status":"Alive"},{"id":17,"photo":"../../images/Llywelyn ap Emrys.jpg","name":"Llywelyn ap Emrys","birth":"478","pids":[],"gender":"male","mid":9,"fid":8,"house":"House Dolforwyn","status":"Alive"},{"id":18,"photo":"../../images/Gwenhwyfar ferch Eira.jpg","name":"Gwenhwyfar ferch Eira","birth":"481","pids":[],"gender":"female","mid":9,"fid":8,"house":"House Dolforwyn","status":"Alive"},{"id":19,"photo":"../../images/Elen ferch Isolde.jpg","name":"Elen ferch Isolde","birth":"482","pids":[],"gender":"female","mid":13,"fid":10,"house":"House Dolforwyn","status":"Alive"},{"id":20,"photo":"../../images/Owain ap Geraint.jpg","name":"Owain ap Geraint","birth":"485","pids":[],"gender":"male","mid":13,"fid":10,"house":"House Dolforwyn","status":"Alive"}]
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
			        .replace("path", "path stroke-dasharray='2, 2'");
			        
		        args.html = args.html
			        .replace(/stroke=\"*\"/g, "stroke='#049ae5'");
		    }

		});
	}
}

</script>