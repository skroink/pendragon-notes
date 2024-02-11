<div style="width:100%; height:700px;" id="tree"></div>

<script>
  document.onreadystatechange = function () {
     if (document.readyState == "complete") {
     	  let family = new FamilyTree(document.getElementById("tree"), {
            nodeBinding: {
                field_0: "name",
                img_0: "photo"
            },
            template: "john",
            filterBy: {
	            gender: {},
	            house: {}  
            },
            tags: {
	            filter:  {
		            template: "dot"
	            }
            },
            nodes:  [{"id":1,"photo":"https://skroink.github.io/pendragon-notes/images/Eilwen ferch Ealdred.png","name":"Eilwen ferch Ealdred","pids":[6],"gender":"female"},{"id":2,"photo":"https://skroink.github.io/pendragon-notes/images/Seren ferch Arianwen.png","name":"Seren ferch Arianwen","pids":[],"gender":"female","mid":14,"fid":13},{"id":3,"photo":"https://skroink.github.io/pendragon-notes/images/Maelona ferch Eilwen.png","name":"Maelona ferch Eilwen","pids":[],"gender":"female","mid":1,"fid":6},{"id":4,"photo":"https://skroink.github.io/pendragon-notes/images/Madoc ap Gwilym.png","name":"Madoc ap Gwilym","pids":[],"gender":"male","mid":1,"fid":6},{"id":5,"photo":"https://skroink.github.io/pendragon-notes/images/Llywelyn ap Emrys.png","name":"Llywelyn ap Emrys","pids":[],"gender":"female","fid":9},{"id":6,"photo":"https://skroink.github.io/pendragon-notes/images/Gwilym ap Cynric.png","name":"Gwilym ap Cynric","pids":[1],"gender":"male","mid":12,"fid":11},{"id":7,"photo":"https://skroink.github.io/pendragon-notes/images/Gwenhwyfar ferch Eira.png","name":"Gwenhwyfar ferch Eira","pids":[],"gender":"female","fid":9},{"id":8,"photo":"https://skroink.github.io/pendragon-notes/images/Geraint ap Gwilym.png","name":"Geraint ap Gwilym","pids":[],"gender":"male","mid":1,"fid":6},{"id":9,"photo":"https://skroink.github.io/pendragon-notes/images/Emrys ap Bran.png","name":"Emrys ap Bran","pids":[],"gender":"male","mid":14,"fid":13},{"id":10,"photo":"https://skroink.github.io/pendragon-notes/images/Elowen ferch Branwen.png","name":"Elowen ferch Branwen","pids":[],"gender":"female","mid":12,"fid":11},{"id":11,"photo":"https://skroink.github.io/pendragon-notes/images/Cynric ap Gwilym.png","name":"Cynric ap Gwilym","pids":[12],"gender":"male"},{"id":12,"photo":"https://skroink.github.io/pendragon-notes/images/Branwen of Boudica.png","name":"Branwen of Boudica","pids":[11],"gender":"female"},{"id":13,"photo":"https://skroink.github.io/pendragon-notes/images/Bran ap Cynric.png","name":"Bran ap Cynric","pids":[14],"gender":"male","mid":12,"fid":11},{"id":14,"photo":"https://skroink.github.io/pendragon-notes/images/Arianwen ferch Cerdic.png","name":"Arianwen ferch Cerdic","pids":[13],"gender":"female"}]
		})
	}
}
</script>