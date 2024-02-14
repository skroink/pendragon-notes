---
hide:
  - toc
---

| name                                                                           |
| ------------------------------------------------------------------------------ |
| [[Characters/House Dolforwyn/Cynric ap Gwilym.md\|Cynric ap Gwilym]]           |
| [[Characters/House Dolforwyn/Bran ap Cynric.md\|Bran ap Cynric]]               |
| [[Characters/House Dolforwyn/Elowen ferch Branwen.md\|Elowen ferch Branwen]]   |
| [[Characters/House Dolforwyn/Emrys ap Bran.md\|Emrys ap Bran]]                 |
| [[Characters/House Dolforwyn/Branwen of Boudica.md\|Branwen of Boudica]]       |
| [[Characters/House Dolforwyn/Gwilym ap Cynric.md\|Gwilym ap Cynric]]           |
| [[Characters/House Dolforwyn/Llywelyn ap Emrys.md\|Llywelyn ap Emrys]]         |
| [[Characters/House Dolforwyn/Madoc ap Gwilym.md\|Madoc ap Gwilym]]             |
| [[Characters/House Dolforwyn/Geraint ap Gwilym.md\|Geraint ap Gwilym]]         |
| [[Characters/House Dolforwyn/Gwenhwyfar ferch Eira.md\|Gwenhwyfar ferch Eira]] |
| [[Characters/House Dolforwyn/Seren ferch Arianwen.md\|Seren ferch Arianwen]]   |
| [[Characters/House Dolforwyn/Maelona ferch Eilwen.md\|Maelona ferch Eilwen]]   |


<div style="width:100%; height:700px;" id="tree"></div>

<script>
  document.onreadystatechange = function () {
     if (document.readyState == "complete") {
     	  let family = new FamilyTree(document.getElementById("tree"), {
            nodeBinding: {field_0: "name",field_1: "status",img_0: "photo" },
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
            nodes:  [{"id":1,"photo":"../../images/Seren ferch Arianwen.jpg","name":"Seren ferch Arianwen","pids":[],"gender":"female","mid":15,"fid":12,"house":"House Dolforwyn","status":"Alive"},{"id":2,"photo":"../../images/Maelona ferch Eilwen.jpg","name":"Maelona ferch Eilwen","pids":[],"gender":"female","mid":13,"fid":5,"house":"House Dolforwyn","status":"Alive"},{"id":3,"photo":"../../images/Madoc ap Gwilym.jpg","name":"Madoc ap Gwilym","pids":[],"gender":"male","mid":13,"fid":5,"house":"House Dolforwyn","status":"Alive"},{"id":4,"photo":"../../images/Llywelyn ap Emrys.jpg","name":"Llywelyn ap Emrys","pids":[],"gender":"male","mid":14,"fid":8,"house":"House Dolforwyn","status":"Alive"},{"id":5,"photo":"../../images/Gwilym ap Cynric.jpg","name":"Gwilym ap Cynric","pids":[13],"gender":"male","mid":11,"fid":10,"house":"House Dolforwyn","status":"Alive"},{"id":6,"photo":"../../images/Gwenhwyfar ferch Eira.jpg","name":"Gwenhwyfar ferch Eira","pids":[],"gender":"female","mid":14,"fid":8,"house":"House Dolforwyn","status":"Alive"},{"id":7,"photo":"../../images/Geraint ap Gwilym.jpg","name":"Geraint ap Gwilym","pids":[],"gender":"male","mid":13,"fid":5,"house":"House Dolforwyn","status":"Alive"},{"id":8,"photo":"../../images/Emrys ap Bran.jpg","name":"Emrys ap Bran","pids":[14],"gender":"male","mid":15,"fid":12,"house":"House Dolforwyn","status":"Alive"},{"id":9,"photo":"../../images/Elowen ferch Branwen.jpg","name":"Elowen ferch Branwen","pids":[],"gender":"female","mid":11,"fid":10,"house":"House Dolforwyn","status":"Deceased"},{"id":10,"photo":"../../images/Cynric ap Gwilym.jpg","name":"Cynric ap Gwilym","pids":[11],"gender":"male","house":"House Dolforwyn","status":"Deceased"},{"id":11,"photo":"../../images/Branwen of Boudica.jpg","name":"Branwen of Boudica","pids":[10],"gender":"female","house":"House Dolforwyn","status":"Alive"},{"id":12,"photo":"../../images/Bran ap Cynric.jpg","name":"Bran ap Cynric","pids":[15],"gender":"male","mid":11,"fid":10,"house":"House Dolforwyn","status":"Alive"},{"id":13,"photo":"../../images/Eilwen ferch Ealdred.jpg","name":"Eilwen ferch Ealdred","pids":[5],"gender":"female","house":"House Llyrith","status":"Alive"},{"id":14,"photo":"../../images/Eira ferch Gwyn.jpg","name":"Eira ferch Gwyn","pids":[8],"gender":"female","house":"House Snowridge","status":"Alive"},{"id":15,"photo":"../../images/Arianwen ferch Cerdic.jpg","name":"Arianwen ferch Cerdic","pids":[12],"gender":"female","house":"House Daelwood","status":"Alive"}]
		})
	}
}
</script>