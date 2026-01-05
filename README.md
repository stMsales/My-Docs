use mprodevdb
switched to db mprodevdb
db.getCollectionInfos({ name: "axisCityMaster" })
[
  {
    name: 'axisCityMaster',
    type: 'collection',
    options: {},
    info: {
      readOnly: false,
      uuid: UUID('be75ff44-51bf-4b9d-9050-73d305622e23')
    },
    idIndex: { v: 2, key: [Object], name: '_id_' }
  }
]
mprodevdb
db.axisCityMaster.getIndexes(
[ { v: 2, key: { _id: 1 }, name: '_id_' } ]
