- 👋 Hi, I’m @Kirishimya
- 👀 I’m interested in embedded
     systems,
     system programming, 
     C programming, 
     C++ programming,
     React,
     Vanilla JavaScript games and
     Processing with JavaScript
     
- 🌱 I’m currently learning 
     IoT programming
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me:
     girossine123@gmail.com

[
    {
        "id": "cd2ef055d43d41b7",
        "type": "tab",
        "label": "Flow 1",
        "disabled": false,
        "info": "",
        "env": []
    },
    {
        "id": "1fc982d4c4d1036a",
        "type": "mqtt in",
        "z": "cd2ef055d43d41b7",
        "name": "",
        "topic": "",
        "qos": "2",
        "datatype": "auto-detect",
        "broker": "b53a7161ce6b2876",
        "nl": false,
        "rap": true,
        "rh": 0,
        "inputs": 0,
        "x": 230,
        "y": 160,
        "wires": [
            [
                "25da65d19ccc64bf"
            ]
        ]
    },
    {
        "id": "541516be707e15ee",
        "type": "mqtt out",
        "z": "cd2ef055d43d41b7",
        "name": "",
        "topic": "",
        "qos": "",
        "retain": "",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "b53a7161ce6b2876",
        "x": 450,
        "y": 360,
        "wires": []
    },
    {
        "id": "25da65d19ccc64bf",
        "type": "ui_gauge",
        "z": "cd2ef055d43d41b7",
        "name": "Motor 1",
        "group": "d9fdd547b5fd859e",
        "order": 0,
        "width": 0,
        "height": 0,
        "gtype": "compass",
        "title": "Motor 1",
        "label": "Graus",
        "format": "{{value}}",
        "min": 0,
        "max": "360",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 460,
        "y": 160,
        "wires": []
    },
    {
        "id": "bac2d4eba175e59a",
        "type": "ui_gauge",
        "z": "cd2ef055d43d41b7",
        "name": "Motor 2",
        "group": "d9fdd547b5fd859e",
        "order": 0,
        "width": 0,
        "height": 0,
        "gtype": "compass",
        "title": "Motor 2",
        "label": "Graus",
        "format": "{{value}}",
        "min": 0,
        "max": "360",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 460,
        "y": 220,
        "wires": []
    },
    {
        "id": "2425d8552877465c",
        "type": "ui_button",
        "z": "cd2ef055d43d41b7",
        "name": "",
        "group": "d9fdd547b5fd859e",
        "order": 2,
        "width": 0,
        "height": 0,
        "passthru": false,
        "label": "Frente",
        "tooltip": "",
        "color": "",
        "bgcolor": "",
        "className": "",
        "icon": "",
        "payload": "frente",
        "payloadType": "str",
        "topic": "topic",
        "topicType": "msg",
        "x": 230,
        "y": 300,
        "wires": [
            [
                "541516be707e15ee"
            ]
        ]
    },
    {
        "id": "41b2513cb390be02",
        "type": "ui_button",
        "z": "cd2ef055d43d41b7",
        "name": "",
        "group": "d9fdd547b5fd859e",
        "order": 2,
        "width": 0,
        "height": 0,
        "passthru": false,
        "label": "Trás",
        "tooltip": "",
        "color": "",
        "bgcolor": "",
        "className": "",
        "icon": "",
        "payload": "frente",
        "payloadType": "str",
        "topic": "topic",
        "topicType": "msg",
        "x": 230,
        "y": 340,
        "wires": [
            [
                "541516be707e15ee"
            ]
        ]
    },
    {
        "id": "c5da3c7dca9e9d8e",
        "type": "ui_button",
        "z": "cd2ef055d43d41b7",
        "name": "",
        "group": "d9fdd547b5fd859e",
        "order": 2,
        "width": 0,
        "height": 0,
        "passthru": false,
        "label": "Esquerda",
        "tooltip": "",
        "color": "",
        "bgcolor": "",
        "className": "",
        "icon": "",
        "payload": "frente",
        "payloadType": "str",
        "topic": "topic",
        "topicType": "msg",
        "x": 240,
        "y": 380,
        "wires": [
            [
                "541516be707e15ee"
            ]
        ]
    },
    {
        "id": "6f71e901893ffbbc",
        "type": "ui_button",
        "z": "cd2ef055d43d41b7",
        "name": "",
        "group": "d9fdd547b5fd859e",
        "order": 2,
        "width": 0,
        "height": 0,
        "passthru": false,
        "label": "Direita",
        "tooltip": "",
        "color": "",
        "bgcolor": "",
        "className": "",
        "icon": "",
        "payload": "frente",
        "payloadType": "str",
        "topic": "topic",
        "topicType": "msg",
        "x": 230,
        "y": 420,
        "wires": [
            [
                "541516be707e15ee"
            ]
        ]
    },
    {
        "id": "a529c65149b5dc2e",
        "type": "mqtt in",
        "z": "cd2ef055d43d41b7",
        "name": "",
        "topic": "",
        "qos": "2",
        "datatype": "auto-detect",
        "broker": "b53a7161ce6b2876",
        "nl": false,
        "rap": true,
        "rh": 0,
        "inputs": 0,
        "x": 230,
        "y": 220,
        "wires": [
            [
                "bac2d4eba175e59a"
            ]
        ]
    },
    {
        "id": "e404f30acd5874b9",
        "type": "ui_switch",
        "z": "cd2ef055d43d41b7",
        "name": "",
        "label": "switch",
        "tooltip": "",
        "group": "d9fdd547b5fd859e",
        "order": 6,
        "width": 0,
        "height": 0,
        "passthru": true,
        "decouple": "false",
        "topic": "topic",
        "topicType": "msg",
        "style": "",
        "onvalue": "true",
        "onvalueType": "bool",
        "onicon": "",
        "oncolor": "",
        "offvalue": "false",
        "offvalueType": "bool",
        "officon": "",
        "offcolor": "",
        "animate": false,
        "className": "",
        "x": 230,
        "y": 580,
        "wires": [
            [
                "2570d81e5559e73e"
            ]
        ]
    },
    {
        "id": "2570d81e5559e73e",
        "type": "function",
        "z": "cd2ef055d43d41b7",
        "name": "function 1",
        "func": "if(msg.payload) {\n    msg.payload = false;\n}\nreturn msg;",
        "outputs": 1,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 380,
        "y": 580,
        "wires": [
            [
                "e404f30acd5874b9"
            ]
        ]
    },
    {
        "id": "73d33457e9b31bfd",
        "type": "debug",
        "z": "cd2ef055d43d41b7",
        "name": "debug 1",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "false",
        "statusVal": "",
        "statusType": "auto",
        "x": 420,
        "y": 500,
        "wires": []
    },
    {
        "id": "41e6af65955b65e5",
        "type": "function",
        "z": "cd2ef055d43d41b7",
        "name": "function 2",
        "func": "\nreturn msg;",
        "outputs": 1,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 240,
        "y": 520,
        "wires": [
            []
        ]
    },
    {
        "id": "b53a7161ce6b2876",
        "type": "mqtt-broker",
        "name": "",
        "broker": "test.mosquitto.org",
        "port": "1883",
        "clientid": "",
        "autoConnect": true,
        "usetls": false,
        "protocolVersion": "4",
        "keepalive": "60",
        "cleansession": true,
        "birthTopic": "",
        "birthQos": "0",
        "birthRetain": "false",
        "birthPayload": "",
        "birthMsg": {},
        "closeTopic": "",
        "closeQos": "0",
        "closeRetain": "false",
        "closePayload": "",
        "closeMsg": {},
        "willTopic": "",
        "willQos": "0",
        "willRetain": "false",
        "willPayload": "",
        "willMsg": {},
        "userProps": "",
        "sessionExpiry": ""
    },
    {
        "id": "d9fdd547b5fd859e",
        "type": "ui_group",
        "name": "Motores",
        "tab": "97e09ee3d32a20dd",
        "order": 1,
        "disp": true,
        "width": "8",
        "collapse": true,
        "className": ""
    },
    {
        "id": "97e09ee3d32a20dd",
        "type": "ui_tab",
        "name": "Aba de Controle",
        "icon": "dashboard",
        "disabled": false,
        "hidden": false
    }
]
