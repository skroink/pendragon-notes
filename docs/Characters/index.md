<div style="width:33vw; height:700px;" id="tree"></div>

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
            nodes:  [{"id":1,"photo":"../images/Eilwen ferch Ealdred.jpeg","name":"Eilwen ferch Ealdred","pids":[6],"gender":"female","house":"House Llyrith"},{"id":2,"photo":"../images/Seren ferch Arianwen.jpeg","name":"Seren ferch Arianwen","pids":[],"gender":"female","mid":14,"fid":13,"house":"House Dolforwyn"},{"id":3,"photo":"../images/Maelona ferch Eilwen.jpeg","name":"Maelona ferch Eilwen","pids":[],"gender":"female","mid":1,"fid":6,"house":"House Dolforwyn"},{"id":4,"photo":"../images/Madoc ap Gwilym.jpeg","name":"Madoc ap Gwilym","pids":[],"gender":"male","mid":1,"fid":6,"house":"House Dolforwyn"},{"id":5,"photo":"../images/Llywelyn ap Emrys.jpeg","name":"Llywelyn ap Emrys","pids":[],"gender":"female","fid":9,"house":"House Dolforwyn"},{"id":6,"photo":"../images/Gwilym ap Cynric.jpeg","name":"Gwilym ap Cynric","pids":[1],"gender":"male","mid":12,"fid":11,"house":"House Dolforwyn"},{"id":7,"photo":"../images/Gwenhwyfar ferch Eira.jpeg","name":"Gwenhwyfar ferch Eira","pids":[],"gender":"female","fid":9,"house":"House Dolforwyn"},{"id":8,"photo":"../images/Geraint ap Gwilym.jpeg","name":"Geraint ap Gwilym","pids":[],"gender":"male","mid":1,"fid":6,"house":"House Dolforwyn"},{"id":9,"photo":"../images/Emrys ap Bran.jpeg","name":"Emrys ap Bran","pids":[],"gender":"male","mid":14,"fid":13,"house":"House Dolforwyn"},{"id":10,"photo":"../images/Elowen ferch Branwen.jpeg","name":"Elowen ferch Branwen","pids":[],"gender":"female","mid":12,"fid":11,"house":"House Dolforwyn"},{"id":11,"photo":"../images/Cynric ap Gwilym.jpeg","name":"Cynric ap Gwilym","pids":[12],"gender":"male","house":"House Dolforwyn"},{"id":12,"photo":"../images/Branwen of Boudica.jpeg","name":"Branwen of Boudica","pids":[11],"gender":"female","house":"House Dolforwyn"},{"id":13,"photo":"../images/Bran ap Cynric.jpeg","name":"Bran ap Cynric","pids":[14],"gender":"male","mid":12,"fid":11,"house":"House Dolforwyn"},{"id":14,"photo":"../images/Arianwen ferch Cerdic.jpeg","name":"Arianwen ferch Cerdic","pids":[13],"gender":"female","house":"House Daelwood"}]
		})
	}
}
</script>