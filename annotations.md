# Annotations (Arrival 10/27/2016)

# Annotations.get

**Overview**

```javascript
const planId = String;
const optionalOptions = {
  comments: boolean, // embed comments into annotations response
};
window.dronedeploy.Annotations.get(planId, optionalOptions)
  .subscribe((annotations) => console.log(annotations))
```

**Example Call**

```javascript
window.dronedeploy.Annotations.get('5730dc11929d2465038183ab', {comments: true})
  .subscribe((annotations) => console.log(annotations))
```

**Example Response**
```javascript
[
  {
    "info": {
      "geometry": [
        {
          "type": "Coords",
          "value": {
            "lat": 35.92649941843441,
            "lng": -96.7485022544861
          },
          "isPending": false
        }
      ]
    },
    "userId": "56282ec3098f6b3987e2e937",
    "fillColor": "#40ccde",
    "dateModified": 1477425822658,
    "color": "#00bbd3",
    "comments": [],
    "options": 0,
    "geometry": {
      "lat": 35.92649941843441,
      "lng": -96.7485022544861
    },
    "annotationType": "LOCATION",
    "id": "580fba9ecb5fda701d819131",
    "planId": "5730dc11929d2465038183ab",
    "type": "marker",
    "dateCreation": 1477425822658,
    "description": ""
  },
  {
    "info": {
      "geometry": [
        {
          "type": "Area",
          "value": 3935.274554447226,
          "isPending": false
        }
      ]
    },
    "userId": "56282ec3098f6b3987e2e937",
    "fillColor": "#40ccde",
    "dateModified": 1477425814283,
    "color": "#00bbd3",
    "comments": [],
    "options": 0,
    "geometry": [
      {
        "lat": 35.92754630265763,
        "lng": -96.74921572208406
      },
      {
        "lat": 35.927016346401395,
        "lng": -96.74940884113313
      },
      {
        "lat": 35.92681218197787,
        "lng": -96.74877047538757
      },
      {
        "lat": 35.92742467366698,
        "lng": -96.74858808517457
      }
    ],
    "annotationType": "VOLUME",
    "id": "580fba96cb5fda701d819130",
    "planId": "5730dc11929d2465038183ab",
    "type": "polygon",
    "dateCreation": 1477425814283,
    "description": ""
  },
  {
    "info": {
      "geometry": [
        {
          "isPending": false,
          "type": "Length",
          "value": 93.33897899201712
        }
      ]
    },
    "userId": "56282ec3098f6b3987e2e937",
    "fillColor": "#8c6bc8",
    "dateModified": 1476138774860,
    "color": "#6639b6",
    "comments": [
      {
        "text": "one",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011401456
      },
      {
        "text": "two",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011402317
      },
      {
        "text": "three",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011403352
      },
      {
        "text": "four",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011404088
      },
      {
        "text": "five",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011405104
      },
      {
        "text": "size",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011405920
      },
      {
        "text": "slkdjf",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011406848
      },
      {
        "text": "skdlfj",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011407336
      },
      {
        "text": "kadsjf",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011407833
      },
      {
        "text": "akldfj",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011408320
      },
      {
        "text": "alkdfja",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011408823
      },
      {
        "text": "sdklfj",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011409232
      },
      {
        "text": "asdlkfa",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011409696
      },
      {
        "text": "dskfas",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011410135
      },
      {
        "text": "dkfas",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011410535
      },
      {
        "text": "dfkas",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011411000
      },
      {
        "text": "fkja",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011411482
      },
      {
        "text": "fkjadfkjas",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011411882
      },
      {
        "text": "fkjadfkjasdkfas",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011412303
      },
      {
        "text": "dkfasd",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011412775
      },
      {
        "text": "fkjasd",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011413376
      },
      {
        "text": "fljklkasdjf",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011414288
      },
      {
        "text": "kdjfa",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011414927
      },
      {
        "text": "dskfj",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011415544
      },
      {
        "text": "sdkljf",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011416376
      },
      {
        "text": "asldkjf",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011417503
      },
      {
        "text": "aslkdjf",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011418375
      },
      {
        "text": "asdlkjf",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011419216
      },
      {
        "text": "adslkjfj",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468011420063
      },
      {
        "text": "scroll",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468014897311
      },
      {
        "text": "again",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468014898302
      },
      {
        "text": "one more",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1468014900302
      },
      {
        "text": "i do not like purple.. ",
        "user": "gerson@dronedeploy.com",
        "timestamp": 1468891733791
      }
    ],
    "options": 0,
    "geometry": [
      {
        "lat": 35.926664485076856,
        "lng": -96.74887508153917
      },
      {
        "lat": 35.92582936181789,
        "lng": -96.74878254532815
      }
    ],
    "annotationType": "LINE",
    "id": "57fc1716cb5fda42e3aacd42",
    "planId": "5730dc11929d2465038183ab",
    "type": "Polyline",
    "dateCreation": 1476138774860,
    "description": "no name? "
  },
  {
    "info": {
      "geometry": [
        {
          "isPending": false,
          "type": "Area",
          "value": 2337.570386649136
        }
      ]
    },
    "userId": "56282ec3098f6b3987e2e937",
    "fillColor": "#d9e46a",
    "dateModified": 1476138774855,
    "color": "#ccdb38",
    "comments": [
      {
        "text": "dfasdf",
        "user": "daniel@dronedeploy.com",
        "timestamp": 1467925757466
      }
    ],
    "options": 0,
    "geometry": [
      {
        "lat": 35.926369099926205,
        "lng": -96.74902260303499
      },
      {
        "lat": 35.92579135195309,
        "lng": -96.74922108650209
      },
      {
        "lat": 35.9256653762706,
        "lng": -96.74896359443666
      },
      {
        "lat": 35.926073710512455,
        "lng": -96.74858272075653
      }
    ],
    "annotationType": "AREA",
    "id": "57fc1716cb5fda42e3aacd41",
    "planId": "5730dc11929d2465038183ab",
    "type": "Polygon",
    "dateCreation": 1476138774855,
    "description": ""
  }
]
```