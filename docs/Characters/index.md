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
            nodes:  [{"id":1,"photo":"../images/Eilwen ferch Ealdred.jpg","name":"Eilwen ferch Ealdred","pids":[7],"gender":"female","house":"House Llyrith","status":"Alive"},{"id":2,"photo":"../images/Eira ferch Gwyn.jpg","name":"Eira ferch Gwyn","pids":[11],"gender":"female","house":"House Snowridge","status":"Alive"},{"id":3,"photo":"../images/Seren ferch Arianwen.jpg","name":"Seren ferch Arianwen","pids":[],"gender":"female","mid":15,"fid":14,"house":"House Dolforwyn","status":"Alive"},{"id":4,"photo":"../images/Maelona ferch Eilwen.jpg","name":"Maelona ferch Eilwen","pids":[],"gender":"female","mid":1,"fid":7,"house":"House Dolforwyn","status":"Alive"},{"id":5,"photo":"../images/Madoc ap Gwilym.jpg","name":"Madoc ap Gwilym","pids":[],"gender":"male","mid":1,"fid":7,"house":"House Dolforwyn","status":"Alive"},{"id":6,"photo":"../images/Llywelyn ap Emrys.jpg","name":"Llywelyn ap Emrys","pids":[],"gender":"female","mid":2,"fid":11,"house":"House Dolforwyn","status":"Alive"},{"id":7,"photo":"../images/Gwilym ap Cynric.jpg","name":"Gwilym ap Cynric","pids":[1],"gender":"male","mid":13,"fid":8,"house":"House Dolforwyn","status":"Alive"},{"id":8,"photo":"../images/Cynric ap Gwilym.jpg","name":"Cynric ap Gwilym","pids":[13],"gender":"male","house":"House Dolforwyn","status":"Deceased"},{"id":9,"photo":"../images/Gwenhwyfar ferch Eira.jpg","name":"Gwenhwyfar ferch Eira","pids":[],"gender":"female","mid":2,"fid":11,"house":"House Dolforwyn","status":"Alive"},{"id":10,"photo":"../images/Geraint ap Gwilym.jpg","name":"Geraint ap Gwilym","pids":[],"gender":"male","mid":1,"fid":7,"house":"House Dolforwyn","status":"Alive"},{"id":11,"photo":"../images/Emrys ap Bran.jpg","name":"Emrys ap Bran","pids":[2],"gender":"male","mid":15,"fid":14,"house":"House Dolforwyn","status":"Alive"},{"id":12,"photo":"../images/Elowen ferch Branwen.jpg","name":"Elowen ferch Branwen","pids":[],"gender":"female","mid":13,"fid":8,"house":"House Dolforwyn","status":"Deceased"},{"id":13,"photo":"../images/Branwen of Boudica.jpg","name":"Branwen of Boudica","pids":[8],"gender":"female","house":"House Dolforwyn","status":"Alive"},{"id":14,"photo":"../images/Bran ap Cynric.jpg","name":"Bran ap Cynric","pids":[15],"gender":"male","mid":13,"fid":8,"house":"House Dolforwyn","status":"Alive"},{"id":15,"photo":"../images/Arianwen ferch Cerdic.jpg","name":"Arianwen ferch Cerdic","pids":[14],"gender":"female","house":"House Daelwood","status":"Alive"}]
		})
	}
}
</script>