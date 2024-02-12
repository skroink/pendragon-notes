<div style="width:700px; height:700px;" id="tree"></div>

<script>
  document.onreadystatechange = function () {
     if (document.readyState == "complete") {
     	  let family = new FamilyTree(document.getElementById("tree"), {
            nodeBinding: {field_0: "name",field_1: "title",field_2: "house",img_0: "photo" },
            siblingSpread: 150,
            mouseScrool: FamilyTree.none,
            template: "john",
            editForm: {
            photoBinding: "photo",
            buttons: null
            },
            filterBy: {
	            gender: {},
	            house: {}  
            },
            nodes:  [{"id":1,"photo":"../images/Eira ferch Gwyn.jpg","name":"Eira ferch Gwyn","pids":[10],"gender":"female","house":"House Snowridge"},{"id":2,"photo":"../images/Eilwen ferch Ealdred.jpg","name":"Eilwen ferch Ealdred","pids":[8],"gender":"female","house":"House Llyrith"},{"id":3,"photo":"../images/Maelona ferch Eilwen.jpg","name":"Maelona ferch Eilwen","pids":[],"gender":"female","mid":2,"fid":8,"house":"House Dolforwyn"},{"id":4,"photo":"../images/Seren ferch Arianwen.jpg","name":"Seren ferch Arianwen","pids":[],"gender":"female","mid":15,"fid":12,"house":"House Dolforwyn"},{"id":5,"photo":"../images/Madoc ap Gwilym.jpg","name":"Madoc ap Gwilym","pids":[],"gender":"male","mid":2,"fid":8,"house":"House Dolforwyn"},{"id":6,"photo":"../images/Llywelyn ap Emrys.jpg","name":"Llywelyn ap Emrys","pids":[],"gender":"female","mid":1,"fid":10,"house":"House Dolforwyn"},{"id":7,"photo":"../images/Gwenhwyfar ferch Eira.jpg","name":"Gwenhwyfar ferch Eira","pids":[],"gender":"female","mid":1,"fid":10,"house":"House Dolforwyn"},{"id":8,"photo":"../images/Gwilym ap Cynric.jpg","name":"Gwilym ap Cynric","pids":[2],"gender":"male","mid":14,"fid":13,"house":"House Dolforwyn"},{"id":9,"photo":"../images/Geraint ap Gwilym.jpg","name":"Geraint ap Gwilym","pids":[],"gender":"male","mid":2,"fid":8,"house":"House Dolforwyn"},{"id":10,"photo":"../images/Emrys ap Bran.jpg","name":"Emrys ap Bran","pids":[1],"gender":"male","mid":15,"fid":12,"house":"House Dolforwyn"},{"id":11,"photo":"../images/Elowen ferch Branwen.jpg","name":"Elowen ferch Branwen","pids":[],"gender":"female","mid":14,"fid":13,"house":"House Dolforwyn"},{"id":12,"photo":"../images/Bran ap Cynric.jpg","name":"Bran ap Cynric","pids":[15],"gender":"male","mid":14,"fid":13,"house":"House Dolforwyn"},{"id":13,"photo":"../images/Cynric ap Gwilym.jpg","name":"Cynric ap Gwilym","pids":[14],"gender":"male","house":"House Dolforwyn"},{"id":14,"photo":"../images/Branwen of Boudica.jpg","name":"Branwen of Boudica","pids":[13],"gender":"female","house":"House Dolforwyn"},{"id":15,"photo":"../images/Arianwen ferch Cerdic.jpg","name":"Arianwen ferch Cerdic","pids":[12],"gender":"female","house":"House Daelwood"}]
		})
	}
}
</script>