

mutation{
  createOrganization(input: {
    orgName:"Random org",
    orgAddress:"random address",
    phone:134525,
    email:"sraf@hji.gyf"
  }) {
    id
    orgAddress
    email
    phone
  }
}

query {
  getOrganization(id: "70b572b7-17d5-4197-80d4-98bf39e627ae"){
  orgName
  }
}