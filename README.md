# road-segment-color-ranges

### for IRI  
`insert into iroads (key,value) values ("iri-ranges",{"dataType":"color_range","rangeFor":"iri", "ranges": {  
    "r0": {  
      "from": 3,  
      "to": 4  
    },  
    "r1": {  
      "from": 4,  
      "to": 5  
    },  
    "r2": {  
      "from": 5,  
      "to": 6  
    },  
    "r3": {  
      "from": 6,  
      "to": 8  
    },  
    "r4": {  
      "from": 8,  
      "to": 100  
    }  
  }})  RETURNING *;`  
  
  ### for IRI_ML  
`insert into iroads (key,value) values ("iri-ml-ranges",{"dataType":"color_range","rangeFor":"iri_ml", "ranges": {  
    "r0": {  
      "from": 3,  
      "to": 4  
    },  
    "r1": {  
      "from": 4,  
      "to": 5  
    },  
    "r2": {  
      "from": 5,  
      "to": 6  
    },  
    "r3": {  
      "from": 6,  
      "to": 8  
    },  
    "r4": {  
      "from": 8,  
      "to": 100  
    }  
  }})  RETURNING *;`  
  
    
  ### for average speed
  `insert into iroads (key,value) values ("avgSpeed-ranges",{  
  "dataType": "color_range",  
  "rangeFor": "avgSpeed",  
  "ranges": {  
    "r0": {  
      "from": 0,  
      "to": 10  
    },  
    "r1": {  
      "from": 10,  
      "to": 20  
    },  
    "r2": {  
      "from": 20,  
      "to": 30  
    },  
    "r3": {  
      "from": 30,  
      "to": 40  
    },  
    "r4": {  
      "from": 40,  
      "to": 200  
    }  
  }  
})  RETURNING *;`  
