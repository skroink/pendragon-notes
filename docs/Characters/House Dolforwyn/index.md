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
            nodes:  [{"id":1,"photo":"../../images/Owain ap Geraint.jpg","name":"Owain ap Geraint","pids":[],"gender":"male","mid":16,"fid":8,"house":"House Dolforwyn","status":"Alive"},{"id":2,"photo":"../../images/Eira ferch Gwyn.jpg","name":"Eira ferch Gwyn","pids":[12],"gender":"female","house":"House Snowridge","status":"Alive"},{"id":3,"photo":"../../images/Elen ferch Isolde.jpg","name":"Elen ferch Isolde","pids":[],"gender":"female","mid":16,"fid":8,"house":"House Dolforwyn","status":"Alive"},{"id":4,"photo":"../../images/Seren ferch Arianwen.jpg","name":"Seren ferch Arianwen","pids":[],"gender":"female","mid":18,"fid":13,"house":"House Dolforwyn","status":"Alive"},{"id":5,"photo":"../../images/Maelona ferch Eilwen.jpg","name":"Maelona ferch Eilwen","pids":[],"gender":"female","mid":17,"fid":11,"house":"House Dolforwyn","status":"Alive"},{"id":6,"photo":"../../images/Gwenhwyfar ferch Eira.jpg","name":"Gwenhwyfar ferch Eira","pids":[],"gender":"female","mid":2,"fid":12,"house":"House Dolforwyn","status":"Alive"},{"id":7,"photo":"../../images/Madoc ap Gwilym.jpg","name":"Madoc ap Gwilym","pids":[],"gender":"male","mid":17,"fid":11,"house":"House Dolforwyn","status":"Alive"},{"id":8,"photo":"../../images/Geraint ap Gwilym.jpg","name":"Geraint ap Gwilym","pids":[16],"gender":"male","mid":17,"fid":11,"house":"House Dolforwyn","status":"Alive"},{"id":9,"photo":"../../images/Llywelyn ap Emrys.jpg","name":"Llywelyn ap Emrys","pids":[],"gender":"male","mid":2,"fid":12,"house":"House Dolforwyn","status":"Alive"},{"id":10,"photo":"../../images/Cynric ap Gwilym.jpg","name":"Cynric ap Gwilym","pids":[15],"gender":"male","house":"House Dolforwyn","status":"Deceased"},{"id":11,"photo":"../../images/Gwilym ap Cynric.jpg","name":"Gwilym ap Cynric","pids":[17],"gender":"male","mid":15,"fid":10,"house":"House Dolforwyn","status":"Alive"},{"id":12,"photo":"../../images/Emrys ap Bran.jpg","name":"Emrys ap Bran","pids":[2],"gender":"male","mid":18,"fid":13,"house":"House Dolforwyn","status":"Alive"},{"id":13,"photo":"../../images/Bran ap Cynric.jpg","name":"Bran ap Cynric","pids":[18],"gender":"male","mid":15,"fid":10,"house":"House Dolforwyn","status":"Alive"},{"id":14,"photo":"../../images/Elowen ferch Branwen.jpg","name":"Elowen ferch Branwen","pids":[],"gender":"female","mid":15,"fid":10,"house":"House Dolforwyn","status":"Deceased"},{"id":15,"photo":"../../images/Branwen of Boudica.jpg","name":"Branwen of Boudica","pids":[10],"gender":"female","house":"House Dolforwyn","status":"Alive"},{"id":16,"photo":"../../images/Isolde of Ravenshaw.jpg","name":"Isolde of Ravenshaw","pids":[8],"gender":"female","house":"House Ravenshaw","status":"Alive"},{"id":17,"photo":"../../images/Eilwen ferch Ealdred.jpg","name":"Eilwen ferch Ealdred","pids":[11],"gender":"female","house":"House Llyrith","status":"Alive"},{"id":18,"photo":"../../images/Arianwen ferch Cerdic.jpg","name":"Arianwen ferch Cerdic","pids":[13],"gender":"female","house":"House Daelwood","status":"Alive"}]
		})
	}
}
</script>