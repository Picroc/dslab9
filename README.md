# dslab9

## All members are running

**rs.status()** on primary
```
{
        "set" : "rs0",
        "date" : ISODate("2019-10-31T11:46:13.543Z"),
        "myState" : 1,
        "term" : NumberLong(13),
        "syncingTo" : "",
        "syncSourceHost" : "",
        "syncSourceId" : -1,
        "heartbeatIntervalMillis" : NumberLong(2000),
        "majorityVoteCount" : 2,
        "writeMajorityCount" : 2,
        "optimes" : {
                "lastCommittedOpTime" : {
                        "ts" : Timestamp(1572522368, 1),
                        "t" : NumberLong(13)
                },
                "lastCommittedWallTime" : ISODate("2019-10-31T11:46:08.417Z"),
                "readConcernMajorityOpTime" : {
                        "ts" : Timestamp(1572522368, 1),
                        "t" : NumberLong(13)
                },
                "readConcernMajorityWallTime" : ISODate("2019-10-31T11:46:08.417Z"),
                "appliedOpTime" : {
                        "ts" : Timestamp(1572522368, 1),
                        "t" : NumberLong(13)
                },
                "durableOpTime" : {
                        "ts" : Timestamp(1572522368, 1),
                        "t" : NumberLong(13)
                },
                "lastAppliedWallTime" : ISODate("2019-10-31T11:46:08.417Z"),
                "lastDurableWallTime" : ISODate("2019-10-31T11:46:08.417Z")
        },
        "lastStableRecoveryTimestamp" : Timestamp(1572522344, 2),
        "lastStableCheckpointTimestamp" : Timestamp(1572522344, 2),
        "electionCandidateMetrics" : {
                "lastElectionReason" : "stepUpRequestSkipDryRun",
                "lastElectionDate" : ISODate("2019-10-31T11:31:24.286Z"),
                "termAtElection" : NumberLong(13),
                "lastCommittedOpTimeAtElection" : {
                        "ts" : Timestamp(1572521483, 1),
                        "t" : NumberLong(12)
                },
                "lastSeenOpTimeAtElection" : {
                        "ts" : Timestamp(1572521483, 1),
                        "t" : NumberLong(12)
                },
                "numVotesNeeded" : 2,
                "priorityAtElection" : 1,
                "electionTimeoutMillis" : NumberLong(10000),
                "priorPrimaryMemberId" : 2,
                "numCatchUpOps" : NumberLong(808464432),
                "newTermStartDate" : ISODate("2019-10-31T11:31:24.919Z"),
                "wMajorityWriteAvailabilityDate" : ISODate("2019-10-31T11:31:26.341Z")
        },
        "members" : [
                {
                        "_id" : 0,
                        "name" : "ip-172-31-41-213:27017",
                        "ip" : "172.31.41.213",
                        "health" : 1,
                        "state" : 1,
                        "stateStr" : "PRIMARY",
                        "uptime" : 3965,
                        "optime" : {
                                "ts" : Timestamp(1572522368, 1),
                                "t" : NumberLong(13)
                        },
                        "optimeDate" : ISODate("2019-10-31T11:46:08Z"),
                        "syncingTo" : "",
                        "syncSourceHost" : "",
                        "syncSourceId" : -1,
                        "infoMessage" : "",
                        "electionTime" : Timestamp(1572521484, 1),
                        "electionDate" : ISODate("2019-10-31T11:31:24Z"),
                        "configVersion" : 3,
                        "self" : true,
                        "lastHeartbeatMessage" : ""
                },
                {
                        "_id" : 1,
                        "name" : "mongoInstance2:27017",
                        "ip" : "172.31.47.88",
                        "health" : 1,
                        "state" : 2,
                        "stateStr" : "SECONDARY",
                        "uptime" : 1766,
                        "optime" : {
                                "ts" : Timestamp(1572522368, 1),
                                "t" : NumberLong(13)
                        },
                        "optimeDurable" : {
                                "ts" : Timestamp(1572522368, 1),
                                "t" : NumberLong(13)
                        },
                        "optimeDate" : ISODate("2019-10-31T11:46:08Z"),
                        "optimeDurableDate" : ISODate("2019-10-31T11:46:08Z"),
                        "lastHeartbeat" : ISODate("2019-10-31T11:46:12.396Z"),
                        "lastHeartbeatRecv" : ISODate("2019-10-31T11:46:12.396Z"),
                        "pingMs" : NumberLong(0),
                        "lastHeartbeatMessage" : "",
                        "syncingTo" : "ip-172-31-41-213:27017",
                        "syncSourceHost" : "ip-172-31-41-213:27017",
                        "syncSourceId" : 0,
                        "infoMessage" : "",
                        "configVersion" : 3
                },
                {
                        "_id" : 2,
                        "name" : "mongoInstance3:27017",
                        "ip" : "172.31.43.102",
                        "health" : 1,
                        "state" : 2,
                        "stateStr" : "SECONDARY",
                        "uptime" : 480,
                        "optime" : {
                                "ts" : Timestamp(1572522368, 1),
                                "t" : NumberLong(13)
                        },
                        "optimeDurable" : {
                                "ts" : Timestamp(1572522368, 1),
                                "t" : NumberLong(13)
                        },
                        "optimeDate" : ISODate("2019-10-31T11:46:08Z"),
                        "optimeDurableDate" : ISODate("2019-10-31T11:46:08Z"),
                        "lastHeartbeat" : ISODate("2019-10-31T11:46:12.716Z"),
                        "lastHeartbeatRecv" : ISODate("2019-10-31T11:46:12.280Z"),
                        "pingMs" : NumberLong(0),
                        "lastHeartbeatMessage" : "",
                        "syncingTo" : "ip-172-31-41-213:27017",
                        "syncSourceHost" : "ip-172-31-41-213:27017",
                        "syncSourceId" : 0,
                        "infoMessage" : "",
                        "configVersion" : 3
                }
        ],
        "ok" : 1,
        "$clusterTime" : {
                "clusterTime" : Timestamp(1572522368, 1),
                "signature" : {
                        "hash" : BinData(0,"AAAAAAAAAAAAAAAAAAAAAAAAAAA="),
                        "keyId" : NumberLong(0)
                }
        },
        "operationTime" : Timestamp(1572522368, 1)
}
```

**rs.conf()** on primary
```
{
        "_id" : "rs0",
        "version" : 3,
        "protocolVersion" : NumberLong(1),
        "writeConcernMajorityJournalDefault" : true,
        "members" : [
                {
                        "_id" : 0,
                        "host" : "ip-172-31-41-213:27017",
                        "arbiterOnly" : false,
                        "buildIndexes" : true,
                        "hidden" : false,
                        "priority" : 1,
                        "tags" : {

                        },
                        "slaveDelay" : NumberLong(0),
                        "votes" : 1
                },
                {
                        "_id" : 1,
                        "host" : "mongoInstance2:27017",
                        "arbiterOnly" : false,
                        "buildIndexes" : true,
                        "hidden" : false,
                        "priority" : 1,
                        "tags" : {

                        },
                        "slaveDelay" : NumberLong(0),
                        "votes" : 1
                },
                {
                        "_id" : 2,
                        "host" : "mongoInstance3:27017",
                        "arbiterOnly" : false,
                        "buildIndexes" : true,
                        "hidden" : false,
                        "priority" : 1,
                        "tags" : {

                        },
                        "slaveDelay" : NumberLong(0),
                        "votes" : 1
                }
        ],
        "settings" : {
                "chainingAllowed" : true,
                "heartbeatIntervalMillis" : 2000,
                "heartbeatTimeoutSecs" : 10,
                "electionTimeoutMillis" : 10000,
                "catchUpTimeoutMillis" : -1,
                "catchUpTakeoverDelayMillis" : 30000,
                "getLastErrorModes" : {

                },
                "getLastErrorDefaults" : {
                        "w" : 1,
                        "wtimeout" : 0
                },
                "replicaSetId" : ObjectId("5db9eb07a8e91f453277a33b")
        }
}
```
### Screen at this state
![Image](https://i.imgur.com/cKCyTlT.png)

## Now VPS 1 dropped

**rs.status()** from VPS2
```
{
	"set" : "rs0",
	"date" : ISODate("2019-10-31T11:58:06.704Z"),
	"myState" : 1,
	"term" : NumberLong(14),
	"syncingTo" : "",
	"syncSourceHost" : "",
	"syncSourceId" : -1,
	"heartbeatIntervalMillis" : NumberLong(2000),
	"majorityVoteCount" : 2,
	"writeMajorityCount" : 2,
	"optimes" : {
		"lastCommittedOpTime" : {
			"ts" : Timestamp(1572523084, 1),
			"t" : NumberLong(14)
		},
		"lastCommittedWallTime" : ISODate("2019-10-31T11:58:04.979Z"),
		"readConcernMajorityOpTime" : {
			"ts" : Timestamp(1572523084, 1),
			"t" : NumberLong(14)
		},
		"readConcernMajorityWallTime" : ISODate("2019-10-31T11:58:04.979Z"),
		"appliedOpTime" : {
			"ts" : Timestamp(1572523084, 1),
			"t" : NumberLong(14)
		},
		"durableOpTime" : {
			"ts" : Timestamp(1572523084, 1),
			"t" : NumberLong(14)
		},
		"lastAppliedWallTime" : ISODate("2019-10-31T11:58:04.979Z"),
		"lastDurableWallTime" : ISODate("2019-10-31T11:58:04.979Z")
	},
	"lastStableRecoveryTimestamp" : Timestamp(1572523044, 1),
	"lastStableCheckpointTimestamp" : Timestamp(1572523044, 1),
	"electionCandidateMetrics" : {
		"lastElectionReason" : "stepUpRequestSkipDryRun",
		"lastElectionDate" : ISODate("2019-10-31T11:53:44.295Z"),
		"termAtElection" : NumberLong(14),
		"lastCommittedOpTimeAtElection" : {
			"ts" : Timestamp(1572522814, 1),
			"t" : NumberLong(13)
		},
		"lastSeenOpTimeAtElection" : {
			"ts" : Timestamp(1572522814, 1),
			"t" : NumberLong(13)
		},
		"numVotesNeeded" : 2,
		"priorityAtElection" : 1,
		"electionTimeoutMillis" : NumberLong(10000),
		"priorPrimaryMemberId" : 0,
		"numCatchUpOps" : NumberLong(27017),
		"newTermStartDate" : ISODate("2019-10-31T11:53:44.971Z"),
		"wMajorityWriteAvailabilityDate" : ISODate("2019-10-31T11:53:45.850Z")
	},
	"members" : [
		{
			"_id" : 0,
			"name" : "ip-172-31-41-213:27017",
			"ip" : "172.31.41.213",
			"health" : 0,
			"state" : 8,
			"stateStr" : "(not reachable/healthy)",
			"uptime" : 0,
			"optime" : {
				"ts" : Timestamp(0, 0),
				"t" : NumberLong(-1)
			},
			"optimeDurable" : {
				"ts" : Timestamp(0, 0),
				"t" : NumberLong(-1)
			},
			"optimeDate" : ISODate("1970-01-01T00:00:00Z"),
			"optimeDurableDate" : ISODate("1970-01-01T00:00:00Z"),
			"lastHeartbeat" : ISODate("2019-10-31T11:58:06.130Z"),
			"lastHeartbeatRecv" : ISODate("2019-10-31T11:53:44.437Z"),
			"pingMs" : NumberLong(0),
			"lastHeartbeatMessage" : "Error connecting to ip-172-31-41-213:27017 (172.31.41.213:27017) :: caused by :: No route to host",
			"syncingTo" : "",
			"syncSourceHost" : "",
			"syncSourceId" : -1,
			"infoMessage" : "",
			"configVersion" : -1
		},
		{
			"_id" : 1,
			"name" : "mongoInstance2:27017",
			"ip" : "127.0.0.1",
			"health" : 1,
			"state" : 1,
			"stateStr" : "PRIMARY",
			"uptime" : 4180,
			"optime" : {
				"ts" : Timestamp(1572523084, 1),
				"t" : NumberLong(14)
			},
			"optimeDate" : ISODate("2019-10-31T11:58:04Z"),
			"syncingTo" : "",
			"syncSourceHost" : "",
			"syncSourceId" : -1,
			"infoMessage" : "",
			"electionTime" : Timestamp(1572522824, 1),
			"electionDate" : ISODate("2019-10-31T11:53:44Z"),
			"configVersion" : 3,
			"self" : true,
			"lastHeartbeatMessage" : ""
		},
		{
			"_id" : 2,
			"name" : "mongoInstance3:27017",
			"ip" : "172.31.43.102",
			"health" : 1,
			"state" : 2,
			"stateStr" : "SECONDARY",
			"uptime" : 1194,
			"optime" : {
				"ts" : Timestamp(1572523084, 1),
				"t" : NumberLong(14)
			},
			"optimeDurable" : {
				"ts" : Timestamp(1572523084, 1),
				"t" : NumberLong(14)
			},
			"optimeDate" : ISODate("2019-10-31T11:58:04Z"),
			"optimeDurableDate" : ISODate("2019-10-31T11:58:04Z"),
			"lastHeartbeat" : ISODate("2019-10-31T11:58:06.348Z"),
			"lastHeartbeatRecv" : ISODate("2019-10-31T11:58:05.873Z"),
			"pingMs" : NumberLong(0),
			"lastHeartbeatMessage" : "",
			"syncingTo" : "mongoInstance2:27017",
			"syncSourceHost" : "mongoInstance2:27017",
			"syncSourceId" : 1,
			"infoMessage" : "",
			"configVersion" : 3
		}
	],
	"ok" : 1,
	"$clusterTime" : {
		"clusterTime" : Timestamp(1572523084, 1),
		"signature" : {
			"hash" : BinData(0,"AAAAAAAAAAAAAAAAAAAAAAAAAAA="),
			"keyId" : NumberLong(0)
		}
	},
	"operationTime" : Timestamp(1572523084, 1)
}
```

Now it is PRIMARY

**rs.conf()** from VPS2
```
{
	"_id" : "rs0",
	"version" : 3,
	"protocolVersion" : NumberLong(1),
	"writeConcernMajorityJournalDefault" : true,
	"members" : [
		{
			"_id" : 0,
			"host" : "ip-172-31-41-213:27017",
			"arbiterOnly" : false,
			"buildIndexes" : true,
			"hidden" : false,
			"priority" : 1,
			"tags" : {
				
			},
			"slaveDelay" : NumberLong(0),
			"votes" : 1
		},
		{
			"_id" : 1,
			"host" : "mongoInstance2:27017",
			"arbiterOnly" : false,
			"buildIndexes" : true,
			"hidden" : false,
			"priority" : 1,
			"tags" : {
				
			},
			"slaveDelay" : NumberLong(0),
			"votes" : 1
		},
		{
			"_id" : 2,
			"host" : "mongoInstance3:27017",
			"arbiterOnly" : false,
			"buildIndexes" : true,
			"hidden" : false,
			"priority" : 1,
			"tags" : {
				
			},
			"slaveDelay" : NumberLong(0),
			"votes" : 1
		}
	],
	"settings" : {
		"chainingAllowed" : true,
		"heartbeatIntervalMillis" : 2000,
		"heartbeatTimeoutSecs" : 10,
		"electionTimeoutMillis" : 10000,
		"catchUpTimeoutMillis" : -1,
		"catchUpTakeoverDelayMillis" : 30000,
		"getLastErrorModes" : {
			
		},
		"getLastErrorDefaults" : {
			"w" : 1,
			"wtimeout" : 0
		},
		"replicaSetId" : ObjectId("5db9eb07a8e91f453277a33b")
	}
}
```

### Image after Machine1 shutdown

![Image](https://i.imgur.com/2N2jQkG.png)
