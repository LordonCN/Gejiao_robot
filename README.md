[
  {
    "params": {
      "Frequency": 10,
      "Topic": "/apollo/canbus/chassis"
    },
    "transform": {
      "x": 0,
      "y": 0,
      "z": 0,
      "pitch": 0,
      "yaw": 0,
      "roll": 0
    },
    "name": "CAN Bus",
    "parent": null,
    "pluginId": "b0bdc474-ac09-4355-901d-d7012a8c57a8",
    "sortKey": 0,
    "plugin": {
      "isFavored": true,
      "isShared": false,
      "isOwned": false,
      "accessInfo": {
        "userAccessType": "favored",
        "owner": {
          "id": "0d888b00-fa53-47c1-882a-b68391268a11",
          "firstName": "SVL",
          "lastName": "Content"
        }
      },
      "supportedSimulatorVersions": [
        "2021.3",
        "2021.2",
        "2021.2.2",
        "2021.1",
        "2021.1.1"
      ],
      "id": "b0bdc474-ac09-4355-901d-d7012a8c57a8",
      "name": "CAN Bus Sensor",
      "type": "CanBusSensor",
      "category": "sensor",
      "ownerId": "0d888b00-fa53-47c1-882a-b68391268a11",
      "accessType": "public",
      "description": "This sensor sends data about the vehicle chassis. The data includes:\n\t* Speed [m/s]\n\t* Throttle [%]\n\t* Braking [%]\n\t* Steering [+/- %]\n\t* Parking Brake Status [bool]\n\t* High Beam Status [bool]\n\t* Low Beam Status [bool]\n\t* Hazard Light Status [bool]\n\t* Fog Light Status [bool]\n\t* Left Turn Signal Status [bool]\n\t* Right Turn Signal Status [bool]\n\t* Wiper Status [bool]\n\t* Reverse Gear Status [bool]\n\t* Selected Gear [Int]\n\t* Engine Status [bool]\n\t* Engine RPM [RPM]\n\t* GPS Latitude [Latitude]\n\t* GPS Longitude [Longitude]\n\t* Altitude [m]\n\t* Orientation [3D Vector of Euler angles]\n\t* Velocity [3D Vector of m/s]\nSee https://www.svlsimulator.com/docs/simulation-content/sensors-list/#can-bus for more details.",
      "copyright": "LG Electronics Inc.",
      "licenseName": "LG Content",
      "imageUrl": "/api/v1/assets/download/preview/cd38d045-4374-4cf4-a62b-8bfba1128a39",
      "status": "active",
      "owner": {
        "id": "0d888b00-fa53-47c1-882a-b68391268a11",
        "firstName": "SVL",
        "lastName": "Content"
      },
      "shareRequests": []
    },
    "type": "CanBusSensor"
  },
  {
    "params": {
      "Frequency": 12.5,
      "Topic": "/apollo/sensor/gnss/best_pose",
      "Frame": "gps"
    },
    "transform": {
      "x": 0,
      "y": 0,
      "z": 0.070351,
      "pitch": 0,
      "yaw": 0,
      "roll": 0
    },
    "name": "GPS",
    "parent": null,
    "pluginId": "75bbcbfa-fdca-4703-8e82-abf8078f7991",
    "sortKey": 1,
    "plugin": {
      "isFavored": true,
      "isShared": false,
      "isOwned": false,
      "accessInfo": {
        "userAccessType": "favored",
        "owner": {
          "id": "0d888b00-fa53-47c1-882a-b68391268a11",
          "firstName": "SVL",
          "lastName": "Content"
        }
      },
      "supportedSimulatorVersions": [
        "2021.3",
        "2021.2",
        "2021.2.2",
        "2021.1",
        "2021.1.1"
      ],
      "id": "75bbcbfa-fdca-4703-8e82-abf8078f7991",
      "name": "GPS Device Sensor",
      "type": "GpsSensor",
      "category": "sensor",
      "ownerId": "0d888b00-fa53-47c1-882a-b68391268a11",
      "accessType": "public",
      "description": "This sensor outputs the GPS location of the vehicle in Longitude/Latitude and Northing/Easting coordintates.\nSee https://www.svlsimulator.com/docs/simulation-content/sensors-list/#gps-device for more details.",
      "copyright": "LG Electronics Inc.",
      "licenseName": "LG Content",
      "imageUrl": "/api/v1/assets/download/preview/f73de137-d067-47db-9fb7-242aae49b2ad",
      "status": "active",
      "owner": {
        "id": "0d888b00-fa53-47c1-882a-b68391268a11",
        "firstName": "SVL",
        "lastName": "Content"
      },
      "shareRequests": []
    },
    "type": "GpsSensor"
  },
  {
    "params": {
      "Frequency": 12.5,
      "Topic": "/apollo/sensor/gnss/odometry",
      "Frame": "gps"
    },
    "transform": {
      "x": 0,
      "y": 0,
      "z": 0.070351,
      "pitch": 0,
      "yaw": 0,
      "roll": 0
    },
    "name": "GPS Odometry",
    "parent": null,
    "pluginId": "483f7b90-2f76-42ee-82c1-22f02f25f924",
    "sortKey": 2,
    "plugin": {
      "isFavored": true,
      "isShared": false,
      "isOwned": false,
      "accessInfo": {
        "userAccessType": "favored",
        "owner": {
          "id": "0d888b00-fa53-47c1-882a-b68391268a11",
          "firstName": "SVL",
          "lastName": "Content"
        }
      },
      "supportedSimulatorVersions": [
        "2021.3",
        "2021.2",
        "2021.2.2",
        "2021.1",
        "2021.1.1"
      ],
      "id": "483f7b90-2f76-42ee-82c1-22f02f25f924",
      "name": "GPS Odometry Sensor",
      "type": "GpsOdometrySensor",
      "category": "sensor",
      "ownerId": "0d888b00-fa53-47c1-882a-b68391268a11",
      "accessType": "public",
      "description": "This sensor outputs the GPS location of the vehicle in Longitude/Latitude and Northing/Easting coordintates and the vehicle velocity.\nSee https://www.svlsimulator.com/docs/simulation-content/sensors-list/#gps-odometry for more details.",
      "copyright": "LG Electronics Inc.",
      "licenseName": "LG Content",
      "imageUrl": "/api/v1/assets/download/preview/d672c52e-0e1a-494e-a95c-fc52593a119d",
      "status": "active",
      "owner": {
        "id": "0d888b00-fa53-47c1-882a-b68391268a11",
        "firstName": "SVL",
        "lastName": "Content"
      },
      "shareRequests": []
    },
    "type": "GpsOdometrySensor"
  },
  {
    "params": {
      "Frequency": 12.5,
      "Topic": "/apollo/sensor/gnss/ins_stat",
      "Frame": "gps"
    },
    "transform": {
      "x": 0,
      "y": 0,
      "z": 0.070351,
      "pitch": 0,
      "yaw": 0,
      "roll": 0
    },
    "name": "GPS INS Status",
    "parent": null,
    "pluginId": "77250db2-82c9-47dd-9785-c38cc4cb566d",
    "sortKey": 3,
    "plugin": {
      "isFavored": true,
      "isShared": false,
      "isOwned": false,
      "accessInfo": {
        "userAccessType": "favored",
        "owner": {
          "id": "0d888b00-fa53-47c1-882a-b68391268a11",
          "firstName": "SVL",
          "lastName": "Content"
        }
      },
      "supportedSimulatorVersions": [
        "2021.3",
        "2021.2",
        "2021.2.2",
        "2021.1",
        "2021.1.1"
      ],
      "id": "77250db2-82c9-47dd-9785-c38cc4cb566d",
      "name": "GPS-INS Status Sensor",
      "type": "GpsInsSensor",
      "category": "sensor",
      "ownerId": "0d888b00-fa53-47c1-882a-b68391268a11",
      "accessType": "public",
      "description": "This sensor outputs the status of the GPS correction due to INS. The Simulator is an ideal environment in which GPS is always corrected.\nSee https://www.svlsimulator.com/docs/simulation-content/sensors-list/#gps-ins-status for more details.",
      "copyright": "LG Electronics Inc.",
      "licenseName": "LG Content",
      "imageUrl": "/api/v1/assets/download/preview/b78a10b6-effd-4bda-832b-27552043e9e8",
      "status": "active",
      "owner": {
        "id": "0d888b00-fa53-47c1-882a-b68391268a11",
        "firstName": "SVL",
        "lastName": "Content"
      },
      "shareRequests": []
    },
    "type": "GpsInsSensor"
  },
  {
    "params": {
      "Topic": "/apollo/sensor/gnss/imu",
      "Frame": "imu",
      "CorrectedTopic": "/apollo/sensor/gnss/corrected_imu",
      "CorrectedFrame": "imu"
    },
    "transform": {
      "x": 0,
      "y": 0,
      "z": 0.070351,
      "pitch": 0,
      "yaw": 0,
      "roll": 0
    },
    "name": "IMU",
    "parent": null,
    "pluginId": "9c34ec28-627d-4e73-9bb0-9c2aa7e978f5",
    "sortKey": 4,
    "plugin": {
      "isFavored": true,
      "isShared": false,
      "isOwned": false,
      "accessInfo": {
        "userAccessType": "favored",
        "owner": {
          "id": "0d888b00-fa53-47c1-882a-b68391268a11",
          "firstName": "SVL",
          "lastName": "Content"
        }
      },
      "supportedSimulatorVersions": [
        "2021.3",
        "2021.2",
        "2021.2.2",
        "2021.1",
        "2021.1.1"
      ],
      "id": "9c34ec28-627d-4e73-9bb0-9c2aa7e978f5",
      "name": "IMU Sensor",
      "type": "ImuSensor",
      "category": "sensor",
      "ownerId": "0d888b00-fa53-47c1-882a-b68391268a11",
      "accessType": "public",
      "description": "This sensor output at a fixed rate of 100 Hz. IMU publishes data on topics where the 2nd topic has corrected IMU data.\nSee https://www.svlsimulator.com/docs/simulation-content/sensors-list/#imu for more details.",
      "copyright": "LG Electronics Inc.",
      "licenseName": "LG Content",
      "imageUrl": "/api/v1/assets/download/preview/cf06a7ce-85d0-4edd-a1e1-ca11992800c2",
      "status": "active",
      "owner": {
        "id": "0d888b00-fa53-47c1-882a-b68391268a11",
        "firstName": "SVL",
        "lastName": "Content"
      },
      "shareRequests": []
    },
    "type": "ImuSensor"
  },
  {
    "params": {
      "Frequency": 10,
      "MaxDistance": 100,
      "Topic": "/apollo/perception/obstacles"
    },
    "transform": {
      "x": 0,
      "y": 0,
      "z": 0,
      "pitch": 0,
      "yaw": 0,
      "roll": 0
    },
    "name": "3D Ground Truth",
    "parent": null,
    "pluginId": "e3fef197-9724-48ec-b98e-c5a0892d09c4",
    "sortKey": 5,
    "plugin": {
      "isFavored": true,
      "isShared": false,
      "isOwned": false,
      "accessInfo": {
        "userAccessType": "favored",
        "owner": {
          "id": "0d888b00-fa53-47c1-882a-b68391268a11",
          "firstName": "SVL",
          "lastName": "Content"
        }
      },
      "supportedSimulatorVersions": [
        "2021.3",
        "2021.2",
        "2021.2.2",
        "2021.1",
        "2021.1.1"
      ],
      "id": "e3fef197-9724-48ec-b98e-c5a0892d09c4",
      "name": "3D Ground Truth Sensor",
      "type": "PerceptionSensor3D",
      "category": "sensor",
      "ownerId": "0d888b00-fa53-47c1-882a-b68391268a11",
      "accessType": "public",
      "description": "This sensor returns 3D ground truth data for training and creates bounding boxes around the detected objects. The color of the object corresponds to the object's type:\n\t[\n\t\t\"Car\": \"Green\"\n\t\t\"Pedestrian\": \"Yellow\"\n\t\t\"Bicycle\": \"Cyan\"\n\t\t\"Unknown\":  \"Magenta\"\n\t]\nSee https://www.svlsimulator.com/docs/simulation-content/sensors-list/#3d-ground-truth for more details.",
      "copyright": "LG Electronics Inc.",
      "licenseName": "LG Content",
      "imageUrl": "/api/v1/assets/download/preview/fc200028-6393-4dc5-aa5e-4369df4d4e09",
      "status": "active",
      "owner": {
        "id": "0d888b00-fa53-47c1-882a-b68391268a11",
        "firstName": "SVL",
        "lastName": "Content"
      },
      "shareRequests": []
    },
    "type": "PerceptionSensor3D"
  },
  {
    "params": {
      "Frequency": 10,
      "MaxDistance": 100,
      "Topic": "/apollo/perception/traffic_light"
    },
    "transform": {
      "x": 0,
      "y": 0,
      "z": 0,
      "pitch": 0,
      "yaw": 0,
      "roll": 0
    },
    "name": "Signal Sensor",
    "parent": null,
    "pluginId": "c4ba9b81-b274-4c05-b78e-636e61b4590e",
    "sortKey": 6,
    "plugin": {
      "isFavored": true,
      "isShared": false,
      "isOwned": false,
      "accessInfo": {
        "userAccessType": "favored",
        "owner": {
          "id": "0d888b00-fa53-47c1-882a-b68391268a11",
          "firstName": "SVL",
          "lastName": "Content"
        }
      },
      "supportedSimulatorVersions": [
        "2021.3",
        "2021.2",
        "2021.2.2",
        "2021.1",
        "2021.1.1"
      ],
      "id": "c4ba9b81-b274-4c05-b78e-636e61b4590e",
      "name": "Signal Sensor",
      "type": "SignalSensor",
      "category": "sensor",
      "ownerId": "0d888b00-fa53-47c1-882a-b68391268a11",
      "accessType": "public",
      "description": "This sensor returns ground truth data for traffic light signals connected to the current lane of ego vehicle and creates bounding boxes around the detected signals. The color of the bounding box corresponds to the signal's type:\n\t[\n\t\t\"Green\": \"Green\"\n\t\t\"Yellow\": \"Yellow\"\n\t\t\"Red\": \"Red\"\n\t]\nSee https://www.svlsimulator.com/docs/simulation-content/sensors-list/#signal-sensor for more details.",
      "copyright": "LG Electronics Inc.",
      "licenseName": "LG Content",
      "imageUrl": "/api/v1/assets/download/preview/b96c848a-056f-4961-9bcd-4c885e2b083d",
      "status": "active",
      "owner": {
        "id": "0d888b00-fa53-47c1-882a-b68391268a11",
        "firstName": "SVL",
        "lastName": "Content"
      },
      "shareRequests": []
    },
    "type": "SignalSensor"
  },
  {
    "name": "Keyboard Car Control",
    "parent": null,
    "pluginId": "a2ff904a-ff06-4f06-9e45-cb58217a7142",
    "sortKey": 7,
    "plugin": {
      "isFavored": true,
      "isShared": false,
      "isOwned": false,
      "accessInfo": {
        "userAccessType": "favored",
        "owner": {
          "id": "0d888b00-fa53-47c1-882a-b68391268a11",
          "firstName": "SVL",
          "lastName": "Content"
        }
      },
      "supportedSimulatorVersions": [
        "2021.3",
        "2021.2",
        "2021.2.2",
        "2021.1",
        "2021.1.1"
      ],
      "id": "a2ff904a-ff06-4f06-9e45-cb58217a7142",
      "name": "Keyboard Control Sensor",
      "type": "KeyboardControlSensor",
      "category": "sensor",
      "ownerId": "0d888b00-fa53-47c1-882a-b68391268a11",
      "accessType": "public",
      "description": "This sensor is required for a vehicle to accept keyboard control commands. Parameters are not required.\nSee https://www.svlsimulator.com/docs/simulation-content/sensors-list/#keyboard-control for more details.",
      "copyright": "LG Electronics Inc.",
      "licenseName": "LG Content",
      "imageUrl": "/api/v1/assets/download/preview/990aa76e-ecc4-4404-a4fe-7e6736b39082",
      "status": "active",
      "owner": {
        "id": "0d888b00-fa53-47c1-882a-b68391268a11",
        "firstName": "SVL",
        "lastName": "Content"
      },
      "shareRequests": []
    },
    "type": "KeyboardControlSensor"
  },
  {
    "name": "Wheel Car Control",
    "parent": null,
    "pluginId": "3d5dea8d-232a-46ea-9a16-57ef4c99df03",
    "sortKey": 8,
    "plugin": {
      "isFavored": true,
      "isShared": false,
      "isOwned": false,
      "accessInfo": {
        "userAccessType": "favored",
        "owner": {
          "id": "0d888b00-fa53-47c1-882a-b68391268a11",
          "firstName": "SVL",
          "lastName": "Content"
        }
      },
      "supportedSimulatorVersions": [
        "2021.3",
        "2021.2",
        "2021.2.2",
        "2021.1",
        "2021.1.1"
      ],
      "id": "3d5dea8d-232a-46ea-9a16-57ef4c99df03",
      "name": "Wheel Control Sensor",
      "type": "WheelControlSensor",
      "category": "sensor",
      "ownerId": "0d888b00-fa53-47c1-882a-b68391268a11",
      "accessType": "public",
      "description": "This sensor is required for a vehicle to accept Logitech G920 wheel control commands. Parameters are not required.",
      "copyright": "LG Electronics Inc.",
      "licenseName": "LG Content",
      "imageUrl": "/api/v1/assets/download/preview/f7a442e9-8bf3-47e0-b77f-046636cca451",
      "status": "active",
      "owner": {
        "id": "0d888b00-fa53-47c1-882a-b68391268a11",
        "firstName": "SVL",
        "lastName": "Content"
      },
      "shareRequests": []
    },
    "type": "WheelControlSensor"
  },
  {
    "params": {
      "Topic": "/apollo/control",
      "StuckTimeThreshold": 20
    },
    "name": "Apollo Car Control",
    "parent": null,
    "pluginId": "03ea1a65-03ae-4f2e-b670-d7244e48deb4",
    "sortKey": 9,
    "plugin": {
      "isFavored": true,
      "isShared": false,
      "isOwned": false,
      "accessInfo": {
        "userAccessType": "favored",
        "owner": {
          "id": "0d888b00-fa53-47c1-882a-b68391268a11",
          "firstName": "SVL",
          "lastName": "Content"
        }
      },
      "supportedSimulatorVersions": [
        "2021.3",
        "2021.2",
        "2021.2.2",
        "2021.1",
        "2021.1.1"
      ],
      "id": "03ea1a65-03ae-4f2e-b670-d7244e48deb4",
      "name": "Apollo Control Sensor",
      "type": "ApolloControlSensor",
      "category": "sensor",
      "ownerId": "0d888b00-fa53-47c1-882a-b68391268a11",
      "accessType": "public",
      "description": "This sensor is required for a vehicle to subscribe to the control topic of Apollo. This sensor also demonstrates how a user can check when SVL Simulator receives the first control message from the AD stack like Apollo. Based on this time, you can start the rest of the simulation or do some other interesting things.\nSee https://www.svlsimulator.com/docs/simulation-content/sensors-list/#apollo-control for more details.",
      "copyright": "LG Electronics Inc.",
      "licenseName": "LG Content",
      "imageUrl": "/api/v1/assets/download/preview/090891ee-7bb0-4505-bc09-0c49002af43a",
      "status": "active",
      "owner": {
        "id": "0d888b00-fa53-47c1-882a-b68391268a11",
        "firstName": "SVL",
        "lastName": "Content"
      },
      "shareRequests": []
    },
    "type": "ApolloControlSensor"
  },
  {
    "params": {
      "Topic": "/clock"
    },
    "name": "Clock Sensor",
    "parent": null,
    "pluginId": "968f386f-dc0b-485d-ba33-5bb71bff93ef",
    "sortKey": 10,
    "plugin": {
      "isFavored": true,
      "isShared": false,
      "isOwned": false,
      "accessInfo": {
        "userAccessType": "favored",
        "owner": {
          "id": "0d888b00-fa53-47c1-882a-b68391268a11",
          "firstName": "SVL",
          "lastName": "Content"
        }
      },
      "supportedSimulatorVersions": [
        "2021.3",
        "2021.2",
        "2021.2.2",
        "2021.1",
        "2021.1.1"
      ],
      "id": "968f386f-dc0b-485d-ba33-5bb71bff93ef",
      "name": "Clock Sensor",
      "type": "ClockSensor",
      "category": "sensor",
      "ownerId": "0d888b00-fa53-47c1-882a-b68391268a11",
      "accessType": "public",
      "description": "This sensor outputs simulated time to ROS as rosgraph_msgs/Clock message, or to CyberRT as clock message. The only parameter to use is topic/channel name.\nSee https://www.svlsimulator.com/docs/simulation-content/sensors-list/#clock for more details.",
      "copyright": "LG Electronics Inc.",
      "licenseName": "LG Content",
      "imageUrl": "/api/v1/assets/download/preview/fb75d445-2e83-440f-8268-c9d4e65024ae",
      "status": "active",
      "owner": {
        "id": "0d888b00-fa53-47c1-882a-b68391268a11",
        "firstName": "SVL",
        "lastName": "Content"
      },
      "shareRequests": []
    },
    "type": "ClockSensor"
  }
]
