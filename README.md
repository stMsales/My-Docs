SP Filter
Calling SP Filter
SP Filter completed
SP Filter: BEFORE
SP Filter: AFTER
Filtering out proposal
stageKey=
journeyStage=
filtered out=
proposals before filter
proposals after filter







@timestamp:Jan 8, 2026 @ 02:10:23.797 log:2026-01-07 20:40:23 7bea0efd-79a4-43e4-bfb9-d92e69f400c0 655393 matrix-dev-dashboard-fargate-service [http-nio-8080-exec-8] INFO c.m.m.dashboard.util.LoggerUtility - {"timestamp":"2026-01-07 20:40:23","containerName":"matrix-dev-dashboard-fargate-service","sno":"35","methodName":"getDashboardData","origin":"com.mli.mpro.dashboard.service.impl.DashboardServiceImpl:257","message":"SP Filter completed for stageKey=1, proposals after filter=10"} container_id:a99fd8603270433eaf44c73e937c3a6a-0866347682 container_name:matrix-dev-dashboard-fargate-container source:stdout ecs_cluster:matrix-dev-microservices-cluster ecs_task_arn:arn:aws:ecs:ap-south-1:777706696655:task/matrix-dev-microservices-cluster/a99fd8603270433eaf44c73e937c3a6a ecs_task_definition:matrix-dev-dashboard-fargate-container:558 _id:nagwmpsBm2FD2J8XcQOe _type: - _index:mli-dev-matrix-dashboard-fargate-service-2026.01.07 _score: -

@timestamp:Jan 8, 2026 @ 02:10:23.797 container_name:matrix-dev-dashboard-fargate-container source:stdout log:2026-01-07 20:40:23 7bea0efd-79a4-43e4-bfb9-d92e69f400c0 655393 matrix-dev-dashboard-fargate-service [http-nio-8080-exec-8] INFO c.m.m.dashboard.util.LoggerUtility - {"timestamp":"2026-01-07 20:40:23","containerName":"matrix-dev-dashboard-fargate-service","sno":"32","methodName":"getDashboardData","origin":"com.mli.mpro.dashboard.service.impl.DashboardServiceImpl:254","message":"Calling SP Filter for stageKey=1, agentId=655393, proposals before filter=10"} container_id:a99fd8603270433eaf44c73e937c3a6a-0866347682 ecs_cluster:matrix-dev-microservices-cluster ecs_task_arn:arn:aws:ecs:ap-south-1:777706696655:task/matrix-dev-microservices-cluster/a99fd8603270433eaf44c73e937c3a6a ecs_task_definition:matrix-dev-dashboard-fargate-container:558 _id:mqgwmpsBm2FD2J8XcQOe _type: - _index:mli-dev-matrix-dashboard-fargate-service-2026.01.07 _score: -
isSpJourneyCompleted



{
  "_id": {
    "$oid": "695ebeaffcbe3237d138a039"
  },
  "transactionId": {
    "$numberLong": "2000111200"
  },
  "version": "v3",
  "applicationDetails": {
    "createdTime": {
      "$date": "2026-01-07T20:14:39.000Z"
    },
    "applicationStatus": "Initiated",
    "updatedTime": {
      "$date": "2026-01-07T20:14:48.111Z"
    },
    "stage": "1",
    "spStage": "2",
    "formType": "self",
    "posvJourneyFlag": "FALSE",
    "underwritingJourneyFlag": "FALSE",
    "isPOSVReTriggered": false,
    "ckycNumber": "",
    "isCKYCAvailable": "no",
    "isCkycFetchedSuccess": "false",
    "physicalJourneyEnabled": "No",
    "rePolicyNumber": "",
    "schemeType": ""
  },
  "sourcingDetails": {
    "isAgentValidated": false,
    "agentId": "",
    "agentName": "",
    "agencyName": "",
    "agentLocation": "",
    "agentRole": "XAG",
    "agentLevel": "",
    "agentMobileNumber": {
      "$numberLong": "0"
    },
    "raDocumentSharingId": "",
    "raDocumentSharingEmail": "",
    "raDocumentSharingMobile": "",
    "uwAgentJoiningDt": "2000-01-01",
    "agentStatus": "",
    "agentCode": "",
    "agentEmail": "",
    "goCABrokerCode": "",
    "agentLicenseStartdate": "Invalid Date",
    "licenceExpiryDateForAgent": "",
    "reportingManagerCode": "",
    "reportingManagerName": "",
    "spStatus": "",
    "ssnCode": "",
    "specifiedPersonName": "",
    "specifiedPersonCode": "",
    "persistency": "",
    "specifiedPersonDetails": {
      "spName": "",
      "spCode": "SP0069181927",
      "amlStatus": false,
      "amlTrainingExpirationDate": "",
      "ulipStatus": false,
      "ulipTrainingExpirationDate": "",
      "spSSNCode": "655393",
      "isSpJourneyCompleted": false
    },
    "regionalAdvisorId": "",
    "designation": "",
    "agentBranchData": "",
    "sourcingBranchCode": "",
    "regionalAdvisorName": "",
    "regionalAdvisorIdType": "",
    "branchBusinessCode": "",
    "isPosSeller": false,
    "agentPAN": "",
    "agentBranchPincode": "",
    "agentGender": "",
    "campaignId": "",
    "verticalName": "",
    "sellerName": "",
    "campaignLocationOption": "",
    "campaignIdOption": "",
    "campaignLocation": "",
    "referenceID": "",
    "branchMailId": "",
    "mappedAgentId": "",
    "relationshipManagerSupport": "",
    "relationshipManagerCode": "",
    "licenceNum": "NA",
    "partnerCustId": "",
    "rAJourneyApplicable": false,
    "isCkycWipCase": true,
    "agentSegment": ""
  },
  "instantQcFlags": {
    "instantQcEnablement": "",
    "instantQcOspSkip": "",
    "instantQcButtonDisabledUntil": "",
    "instantQcBackflowReceived": false,
    "ivcTriggeredAfterInstaQc": false,
    "isInstantQcTriggered": false
  },
  "channelDetails": {
    "branchCode": "0012",
    "partnerChannel": "",
    "branchName": "",
    "channel": "X",
    "specifiedPersonChannel": {
      "spBranchCode": "0012"
    },
    "originalChannel": "",
    "channelType": ""
  },
  "partyInformation": [
    {
      "partyType": "Proposer",
      "basicDetails": {
        "firstName": "ryryryryyryryryryr",
        "middleName": "",
        "lastName": "Kumar ",
        "gender": "M",
        "dob": {
          "$date": "1986-05-09T00:00:00.000Z"
        },
        "fatherName": "",
        "motherName": "",
        "residentialStatus": "indian",
        "nationalityDetails": {
          "nationality": "indian",
          "nriDetails": {
            "passportNumber": "",
            "typeOfVisa": "",
            "passportIssuingCountry": "",
            "currentCountryOfResidence": "",
            "countryVisitedFrequently": [],
            "countryOfBirth": "",
            "uidIssuingCountry": "",
            "countryOfResidenceAsPerTaxLaw": "",
            "ftinDetails": {
              "isFTINExist": false,
              "multipleFTINDetailsForNRI": [
                {
                  "ftinNumber": "",
                  "ftinIssuingCountry": ""
                }
              ],
              "typeOfForeignIdentification": "",
              "identificationNumber": ""
            },
            "issuingCountry": "",
            "applicationSource": "",
            "passportExpiryDate": {
              "$date": "2026-02-07T20:00:00.000Z"
            },
            "citizenship": "",
            "cityOfBirth": ""
          }
        },
        "marriageDetails": {
          "maritalStatus": "",
          "maidenName": "",
          "spouseAnnualIncome": "",
          "totalInsuranceCoverOnSpouse": "",
          "isPregnant": false,
          "pregnantSince": "",
          "anyComplicationToPregnancy": false,
          "pregnancyComplicationDetails": "",
          "prevAnyComplicationToPregnancy": "",
          "prevPregnancyComplicationDetails": ""
        },
        "education": "Graduate",
        "occupation": "Salaried",
        "annualIncome": "",
        "areBothAddressSame": false,
        "address": [
          {
            "proofType": "",
            "proofNumber": "",
            "proofExpiryDate": "",
            "addressType": "Current",
            "addressDetails": {
              "houseNo": "11/6,NETHAJI NAGAR,KULATHUPALA",
              "area": "YAM,COIMBATORE -",
              "landmark": "",
              "city": "Coimbatore ",
              "state": "TAMIL NADU",
              "pinCode": "641109",
              "country": "",
              "village": "",
              "voterIdOcrStatus": "Not_Initiated",
              "aadhaarOcrStatus": "Not_Initiated"
            }
          },
          {
            "proofType": "",
            "proofNumber": "",
            "proofExpiryDate": "",
            "addressType": "Permanent",
            "addressDetails": {
              "houseNo": "90 a AH Street",
              "area": "",
              "landmark": "",
              "city": "Jalandhar ",
              "state": "",
              "pinCode": "144001",
              "country": "",
              "village": "",
              "voterIdOcrStatus": "Not_Initiated",
              "aadhaarOcrStatus": "Not_Initiated"
            }
          }
        ],
        "preferredLanguageOfCommunication": "English",
        "personalIdentification": {
          "phone": [
            {
              "phoneNumber": "9650989475",
              "stdIsdCode": "",
              "phoneType": "mobileNumber"
            },
            {
              "phoneNumber": "",
              "stdIsdCode": "",
              "phoneType": "alternateMobileNo"
            },
            {
              "phoneNumber": "",
              "stdIsdCode": "",
              "phoneType": "alternateLandlineNo"
            },
            {
              "phoneNumber": "",
              "stdIsdCode": "",
              "phoneType": "communicationAlternateLandlineNo"
            }
          ],
          "panDetails": {
            "panNumber": "AJFPV8829C",
            "isPANExist": false,
            "isPanValidated": false,
            "isDobValidated": false,
            "panOcrFlag": false
          },
          "email": "uditkumar@gmail.com"
        },
        "nachOcrStatus": "Not_Initiated",
        "businessType": "",
        "bdmId": "",
        "enrollerId": "",
        "finderId": "",
        "companyName": "",
        "sourceOfFunds": "",
        "isNPSCustomer": "",
        "isGovtEmployee": "",
        "PreferredMailingAddress": "",
        "hasLastName": false
      },
      "personalIdentification": {
        "phone": [
          {
            "phoneNumber": "9650989475",
            "stdIsdCode": "",
            "phoneType": "mobileNumber",
            "countryName": ""
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "alternateMobileNo"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "alternateLandlineNo"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "communicationAlternateLandlineNo"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "alternateMobileNo",
            "countryName": ""
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "alternateLandlineNo"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "communicationAlternateLandlineNo"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "communicationAlternateMobileNo",
            "countryName": ""
          }
        ],
        "aadhaarDetails": {
          "aadhaarNumber": "",
          "isAadhaarValidated": false,
          "isAadhaarExist": false,
          "aadhaarOCRFlag": false,
          "aadhaarValidationType": "",
          "prePopulationByAadhaarOtp": false,
          "prePopulationByAadhaarOcr": false,
          "reasonForDontHaveAadhaar": {
            "reason": "",
            "neverAppliedState": ""
          },
          "aadhaarOcrStatus": "Not_Initiated",
          "virtualId": "",
          "ekycByAadhaar": "No"
        },
        "enrollment": {
          "enrollmentNo": ""
        },
        "panDetails": {
          "panNumber": "",
          "isPANExist": false,
          "isPanValidated": false,
          "isDobValidated": false,
          "creditScore": "",
          "incomeRange": "",
          "panOcrFlag": false,
          "panOcrStatus": "Not_Initiated",
          "panValidationService": "",
          "panDobVerificationCounter": "",
          "panAadhaarLinkStatus": ""
        },
        "email": "uditkumar@gmail.com",
        "pranNumber": "",
        "abhaId": ""
      },
      "BSE500Company": ""
    },
    {
      "partyType": "Insured",
      "basicDetails": {
        "firstName": "ryryryryyryryryryr",
        "middleName": "",
        "lastName": "Kumar",
        "gender": "M",
        "dob": {
          "$date": "1986-05-09T00:00:00.000Z"
        },
        "fatherName": "",
        "motherName": "",
        "residentialStatus": "",
        "nationalityDetails": {
          "nationality": "",
          "nriDetails": {
            "passportNumber": "",
            "typeOfVisa": "",
            "passportIssuingCountry": "",
            "currentCountryOfResidence": "",
            "countryVisitedFrequently": [],
            "countryOfBirth": "",
            "uidIssuingCountry": "",
            "countryOfResidenceAsPerTaxLaw": "",
            "ftinDetails": {
              "isFTINExist": false,
              "multipleFTINDetailsForNRI": [
                {
                  "ftinNumber": "",
                  "ftinIssuingCountry": ""
                }
              ],
              "typeOfForeignIdentification": "",
              "identificationNumber": ""
            },
            "issuingCountry": "",
            "applicationSource": "",
            "passportExpiryDate": {
              "$date": "2026-02-07T20:00:00.000Z"
            }
          }
        },
        "marriageDetails": {
          "maritalStatus": "",
          "maidenName": "",
          "spouseAnnualIncome": "",
          "totalInsuranceCoverOnSpouse": "",
          "isPregnant": false,
          "pregnantSince": "",
          "anyComplicationToPregnancy": false,
          "pregnancyComplicationDetails": "",
          "prevAnyComplicationToPregnancy": "",
          "prevPregnancyComplicationDetails": ""
        },
        "education": "Graduate",
        "occupation": "Salaried",
        "annualIncome": "",
        "areBothAddressSame": false,
        "address": [
          {
            "proofType": "",
            "proofNumber": "",
            "proofExpiryDate": "",
            "addressType": "Current",
            "addressDetails": {
              "houseNo": "11/6,NETHAJI NAGAR,KULATHUPALA",
              "area": "YAM,COIMBATORE -",
              "landmark": "",
              "city": "Coimbatore ",
              "state": "TAMIL NADU",
              "pinCode": "641109",
              "country": "",
              "village": "",
              "voterIdOcrStatus": "Not_Initiated",
              "aadhaarOcrStatus": "Not_Initiated"
            }
          },
          {
            "proofType": "",
            "proofNumber": "",
            "proofExpiryDate": "",
            "addressType": "Permanent",
            "addressDetails": {
              "houseNo": "90 a AH Street",
              "area": "",
              "landmark": "",
              "city": "Jalandhar ",
              "state": "",
              "pinCode": "144001",
              "country": "",
              "village": "",
              "voterIdOcrStatus": "Not_Initiated",
              "aadhaarOcrStatus": "Not_Initiated"
            }
          }
        ],
        "dobProofType": "",
        "relationshipWithProposer": "",
        "relationshipWithProposerWhenOther": "",
        "preferredLanguageOfCommunication": "",
        "personalIdentification": {
          "phone": [
            {
              "phoneNumber": "9650989475",
              "stdIsdCode": "",
              "phoneType": "mobileNumber"
            },
            {
              "phoneNumber": "",
              "stdIsdCode": "",
              "phoneType": "alternateMobileNo"
            },
            {
              "phoneNumber": "",
              "stdIsdCode": "",
              "phoneType": "alternateLandlineNo"
            },
            {
              "phoneNumber": "",
              "stdIsdCode": "",
              "phoneType": "communicationAlternateLandlineNo"
            }
          ],
          "panDetails": {
            "panNumber": "AJFPV8829C",
            "isPANExist": false,
            "isPanValidated": false,
            "isDobValidated": false,
            "panOcrFlag": false
          },
          "email": "uditkumar@gmail.com"
        },
        "businessType": "",
        "bdmId": "",
        "enrollerId": "",
        "finderId": "",
        "companyName": "",
        "hasLastName": false
      },
      "personalIdentification": {
        "phone": [
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "mobileNumber"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "alternateMobileNo"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "alternateLandlineNo"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "communicationAlternateLandlineNo"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "communicationAlternateMobileNo"
          }
        ],
        "aadhaarDetails": {
          "isAadhaarValidated": false,
          "isAadhaarExist": false,
          "aadhaarOCRFlag": false,
          "aadhaarValidationType": "",
          "prePopulationByAadhaarOtp": false,
          "prePopulationByAadhaarOcr": false,
          "reasonForDontHaveAadhaar": {
            "reason": "",
            "neverAppliedState": ""
          },
          "virtualId": "",
          "ekycByAadhaar": "No"
        },
        "enrollment": {
          "enrollmentNo": ""
        },
        "panDetails": {
          "panNumber": "",
          "isPANExist": false,
          "isPanValidated": false,
          "isDobValidated": false,
          "creditScore": "",
          "incomeRange": "",
          "panOcrFlag": false,
          "panOcrStatus": "Not_Initiated",
          "panValidationService": "",
          "panDobVerificationCounter": "",
          "panAadhaarLinkStatus": "",
          "ekycByPan": "No"
        },
        "email": "",
        "insurerAbhaId": ""
      },
      "BSE500Company": ""
    },
    {
      "partyType": "Payor",
      "basicDetails": {
        "firstName": "ryryryryyryryryryr",
        "middleName": "",
        "lastName": "Kumar",
        "gender": "M",
        "dob": {
          "$date": "1986-05-09T00:00:00.000Z"
        },
        "nationalityDetails": {
          "nationality": "indian",
          "nriDetails": {
            "passportNumber": "",
            "typeOfVisa": "",
            "passportIssuingCountry": "",
            "currentCountryOfResidence": "",
            "countryVisitedFrequently": [],
            "countryOfBirth": "",
            "uidIssuingCountry": "",
            "countryOfResidenceAsPerTaxLaw": "",
            "ftinDetails": {
              "isFTINExist": false,
              "multipleFTINDetailsForNRI": [
                {
                  "ftinNumber": "",
                  "ftinIssuingCountry": ""
                }
              ],
              "typeOfForeignIdentification": "",
              "identificationNumber": ""
            },
            "issuingCountry": "",
            "applicationSource": ""
          }
        },
        "education": "Graduate",
        "occupation": "",
        "annualIncome": "",
        "areBothAddressSame": false,
        "address": [
          {
            "proofType": "",
            "addressType": "Current",
            "addressDetails": {
              "houseNo": "",
              "area": "YAM,COIMBATORE -",
              "landmark": "",
              "city": "",
              "state": "TAMIL NADU",
              "pinCode": "",
              "country": "",
              "village": ""
            }
          },
          {
            "proofType": "",
            "addressType": "Permanent",
            "addressDetails": {
              "houseNo": "90 a AH Street",
              "area": "",
              "landmark": "",
              "city": "Jalandhar ",
              "state": "",
              "pinCode": "144001",
              "country": "",
              "village": ""
            }
          }
        ],
        "relationshipWithProposer": "",
        "personalIdentification": {
          "phone": [
            {
              "phoneNumber": "9650989475",
              "stdIsdCode": "",
              "phoneType": "mobileNumber"
            },
            {
              "phoneNumber": "",
              "stdIsdCode": "",
              "phoneType": "alternateMobileNo"
            },
            {
              "phoneNumber": "",
              "stdIsdCode": "",
              "phoneType": "alternateLandlineNo"
            },
            {
              "phoneNumber": "",
              "stdIsdCode": "",
              "phoneType": "communicationAlternateLandlineNo"
            }
          ],
          "panDetails": {
            "panNumber": "AJFPV8829C",
            "isPANExist": false,
            "isPanValidated": false,
            "isDobValidated": false,
            "panOcrFlag": false
          },
          "email": "uditkumar@gmail.com"
        },
        "businessType": "",
        "bdmId": "",
        "enrollerId": "",
        "finderId": "",
        "companyName": "",
        "hasLastName": false
      },
      "personalIdentification": {
        "phone": [
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": ""
          }
        ],
        "aadhaarDetails": {
          "aadhaarNumber": "",
          "isAadhaarValidated": false,
          "isAadhaarExist": false,
          "aadhaarOCRFlag": false,
          "aadhaarValidationType": "",
          "prePopulationByAadhaarOtp": false,
          "prePopulationByAadhaarOcr": false,
          "reasonForDontHaveAadhaar": {
            "reason": "",
            "neverAppliedState": ""
          },
          "aadhaarOcrStatus": "Not_Initiated",
          "virtualId": "",
          "ekycByAadhaar": "No"
        },
        "enrollment": {
          "enrollmentNo": ""
        },
        "panDetails": {
          "panNumber": "",
          "isPANExist": false,
          "isPanValidated": false,
          "isDobValidated": false,
          "panOcrFlag": false,
          "panOcrStatus": "Not_Initiated",
          "panDobVerificationCounter": "",
          "panAadhaarLinkStatus": ""
        },
        "email": ""
      },
      "bankDetails": {
        "bankAccountNumber": "",
        "accountHolderName": "",
        "micr": "",
        "ifsc": "",
        "bankName": "",
        "bankBranch": ""
      }
    },
    {
      "partyType": "Authorized Signatory",
      "basicDetails": {
        "firstName": "",
        "middleName": "",
        "lastName": "",
        "gender": "M",
        "fatherName": "",
        "motherName": "",
        "nationalityDetails": {
          "nationality": "indian",
          "nriDetails": {
            "passportNumber": "",
            "typeOfVisa": "",
            "passportIssuingCountry": "",
            "currentCountryOfResidence": "",
            "countryVisitedFrequently": [],
            "countryOfBirth": "",
            "uidIssuingCountry": "",
            "countryOfResidenceAsPerTaxLaw": "",
            "ftinDetails": {
              "isFTINExist": false,
              "multipleFTINDetailsForNRI": [
                {
                  "ftinNumber": "",
                  "ftinIssuingCountry": ""
                }
              ],
              "typeOfForeignIdentification": "",
              "identificationNumber": ""
            },
            "issuingCountry": "",
            "applicationSource": "",
            "passportExpiryDate": {
              "$date": "2026-02-07T20:00:00.000Z"
            }
          }
        },
        "marriageDetails": {
          "maritalStatus": "",
          "maidenName": "",
          "spouseAnnualIncome": "",
          "totalInsuranceCoverOnSpouse": "",
          "isPregnant": false,
          "pregnantSince": "",
          "anyComplicationToPregnancy": false,
          "pregnancyComplicationDetails": "",
          "prevAnyComplicationToPregnancy": "",
          "prevPregnancyComplicationDetails": ""
        },
        "occupation": "Salaried",
        "annualIncome": "",
        "areBothAddressSame": false,
        "address": [
          {
            "proofType": "",
            "proofNumber": "",
            "proofExpiryDate": "",
            "addressType": "Current",
            "addressDetails": {
              "houseNo": "",
              "area": "",
              "landmark": "",
              "city": "",
              "state": "",
              "pinCode": "",
              "country": "",
              "village": ""
            }
          },
          {
            "proofType": "",
            "proofNumber": "",
            "addressType": "Permanent",
            "addressDetails": {
              "houseNo": "",
              "area": "",
              "landmark": "",
              "city": "",
              "state": "",
              "pinCode": ""
            }
          }
        ],
        "dobProofType": "",
        "relationshipWithProposerWhenOther": "",
        "businessType": "",
        "bdmId": "",
        "enrollerId": "",
        "finderId": "",
        "companyName": "",
        "relationshipWithCompany": "",
        "directorIdentificationNumber": "",
        "hasLastName": false
      },
      "personalIdentification": {
        "phone": [
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "mobileNumber"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "alternateMobileNo"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "alternateLandlineNo"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "communicationAlternateLandlineNo"
          },
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "communicationAlternateMobileNo"
          }
        ],
        "aadhaarDetails": {
          "aadhaarNumber": "",
          "isAadhaarValidated": false,
          "isAadhaarExist": false,
          "aadhaarOCRFlag": false,
          "aadhaarValidationType": "",
          "prePopulationByAadhaarOtp": false,
          "prePopulationByAadhaarOcr": false,
          "reasonForDontHaveAadhaar": {
            "reason": "",
            "neverAppliedState": ""
          },
          "virtualId": ""
        },
        "enrollment": {
          "enrollmentNo": ""
        },
        "panDetails": {
          "panNumber": "",
          "isPANExist": false,
          "isPanValidated": false,
          "isDobValidated": false,
          "creditScore": "",
          "incomeRange": "",
          "panOcrFlag": false,
          "panOcrStatus": "Not_Initiated",
          "panValidationService": "",
          "panDobVerificationCounter": "",
          "panAadhaarLinkStatus": ""
        },
        "email": ""
      },
      "BSE500Company": ""
    },
    {
      "partyType": "Company",
      "basicDetails": {
        "firstName": "",
        "middleName": "",
        "lastName": "",
        "gender": "",
        "fatherName": "",
        "motherName": "",
        "residentialStatus": "",
        "nationalityDetails": {
          "nationality": "",
          "nriDetails": {
            "passportNumber": "",
            "typeOfVisa": "",
            "passportIssuingCountry": "",
            "currentCountryOfResidence": "",
            "countryVisitedFrequently": [],
            "countryOfBirth": "",
            "uidIssuingCountry": "",
            "countryOfResidenceAsPerTaxLaw": "",
            "ftinDetails": {
              "isFTINExist": false,
              "multipleFTINDetailsForNRI": [
                {
                  "ftinNumber": "",
                  "ftinIssuingCountry": ""
                }
              ],
              "typeOfForeignIdentification": "",
              "identificationNumber": ""
            },
            "issuingCountry": "",
            "applicationSource": "",
            "passportExpiryDate": {
              "$date": "2026-02-07T20:00:00.000Z"
            }
          }
        },
        "marriageDetails": {
          "maritalStatus": "",
          "maidenName": "",
          "spouseAnnualIncome": "",
          "totalInsuranceCoverOnSpouse": "",
          "isPregnant": false,
          "pregnantSince": "",
          "anyComplicationToPregnancy": false,
          "pregnancyComplicationDetails": "",
          "prevAnyComplicationToPregnancy": "",
          "prevPregnancyComplicationDetails": ""
        },
        "annualIncome": "",
        "areBothAddressSame": false,
        "address": [
          {
            "proofType": "",
            "proofNumber": "",
            "proofExpiryDate": "",
            "addressType": "Current",
            "addressDetails": {
              "houseNo": "",
              "area": "",
              "landmark": "",
              "city": "",
              "state": "",
              "pinCode": "",
              "country": "",
              "village": "",
              "voterIdOcrStatus": "",
              "aadhaarOcrStatus": ""
            }
          },
          {
            "proofType": "",
            "proofNumber": "",
            "proofExpiryDate": "",
            "addressType": "Permanent",
            "addressDetails": {
              "houseNo": "",
              "area": "",
              "landmark": "",
              "city": "",
              "state": "",
              "pinCode": "",
              "country": "",
              "village": "",
              "voterIdOcrStatus": "",
              "aadhaarOcrStatus": ""
            }
          }
        ],
        "preferredLanguageOfCommunication": "",
        "nachOcrStatus": "Not_Initiated",
        "businessType": "",
        "bdmId": "",
        "enrollerId": "",
        "finderId": "",
        "companyName": "",
        "companyType": "",
        "organizationType": "",
        "sourceOfFunds": "",
        "hasLastName": false
      },
      "personalIdentification": {
        "phone": [
          {
            "phoneNumber": "",
            "stdIsdCode": "",
            "phoneType": "alternateLandlineNo"
          }
        ],
        "aadhaarDetails": {
          "aadhaarNumber": "",
          "isAadhaarValidated": false,
          "isAadhaarExist": false,
          "aadhaarOCRFlag": false,
          "aadhaarValidationType": "",
          "prePopulationByAadhaarOtp": false,
          "prePopulationByAadhaarOcr": false,
          "reasonForDontHaveAadhaar": {
            "reason": "",
            "neverAppliedState": ""
          },
          "aadhaarOcrStatus": "Not_Initiated",
          "virtualId": ""
        },
        "enrollment": {
          "enrollmentNo": ""
        },
        "panDetails": {
          "panNumber": "",
          "isPANExist": false,
          "isPanValidated": false,
          "isDobValidated": false,
          "creditScore": "",
          "incomeRange": "",
          "panOcrFlag": false,
          "panOcrStatus": "Not_Initiated",
          "panValidationService": "",
          "panDobVerificationCounter": "",
          "panAadhaarLinkStatus": ""
        },
        "email": ""
      },
      "bankDetails": {
        "bankAccountNumber": "",
        "accountHolderName": "",
        "micr": "",
        "ifsc": "",
        "bankName": "",
        "bankBranch": ""
      },
      "BSE500Company": ""
    }
  ],
  "productDetails": [
    {
      "needOfInsurance": "Protection",
      "lifeStage": "Married with no children",
      "objectiveOfInsurance": "Individual Policy",
      "productType": "Traditional",
      "nomineeUnderSection": "",
      "productInfo": {
        "productId": "Axis",
        "productName": "Max Life Smart Wealth Plan",
        "sumAssuredOption": "",
        "sumAssured": "",
        "sumAssuredAvailable": "",
        "isSmoker": false,
        "maturityAge": "",
        "policyTerm": "",
        "premiumType": "",
        "premiumPaymentTerm": "",
        "premiumCommitment": "",
        "dividendOption": "",
        "dividendAdjustment": "",
        "modeOfPayment": "",
        "effectiveDateOfCoverage": "",
        "annualIncome": {
          "$numberLong": "1000000"
        },
        "desiredAnnualIncome": {
          "$numberLong": "0"
        },
        "childDob": {
          "$date": "2026-01-07T20:00:00.000Z"
        },
        "vestingAge": "",
        "isSaveTommorow": false,
        "riderDetails": [
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          },
          {
            "isRiderRequired": false,
            "riderInfo": "",
            "amount": 0,
            "riderTerm": "",
            "riderSumAssured": 0,
            "riderModalPremium": 0
          }
        ],
        "fundSelection": {
          "isFundAllocated": false,
          "isSTPAllocated": false,
          "isDFAAllocated": false,
          "fundInfo": [
            {
              "fundName": "",
              "fundValue": 0
            }
          ],
          "lifecyclePortfolioStrategy": false,
          "triggerBasedPortfolioStrategy": false,
          "fund1": "",
          "fund2": "",
          "triggerPercentage": "",
          "esgFundSelected": "N",
          "isRecommendedFundAllocated": false,
          "nfoFundDetails": {
            "nfoFromFundName": "",
            "nfoToFundName": "",
            "nfoFundPercent": 0
          }
        },
        "secondAnnuitantName": "",
        "secondAnnuitantSex": "",
        "annuityOption": "",
        "deathBenefitForAnnuity": "",
        "deathBenefit": "",
        "incomePeriod": "",
        "premiumBackOption": "",
        "premiumBreakOption": "",
        "firstPremiumBreakOption": "",
        "secondPremiumBreakOption": "",
        "lifeStageEventBenefit": "",
        "customerDiscount": "",
        "isDiabetic": "",
        "smokingHabits": "",
        "variant": "",
        "incomeCategory": "",
        "coverMultiple": "",
        "incomePayoutFrequency": "",
        "incomePayoutOption": "",
        "annuityType": "",
        "defermentPeriod": "",
        "secondAnnuitantRelationship": "",
        "secondAnnuitantRelationshipWhenOthers": "",
        "isSecondAnnuitantPANExist": false,
        "secondAnnuitantPanNumber": "",
        "annuityAmount": "",
        "isSecondAnnuitantPanValidated": "false",
        "isSecondAnnuitantDobValidated": "false",
        "isPurchasePrice": false,
        "secondAnnuitantPanAadhaarStatus": "",
        "secondAnnuitantPanAadhaarCounter": "",
        "secondAnnuitantPanAadhaarResponseTime": "",
        "solutionName": "",
        "smartWithdrawalPayoutPercentage": "",
        "waiverofPremiumBenefit": "",
        "smartWithdrawalPlan": "",
        "smartWithdrawalPayoutMode": "",
        "smartWithdrawalPayoutStartYear": 0,
        "pcb": "no",
        "cashBonus": "",
        "isAnnuityProduct": "",
        "familyIncomeOption": "",
        "SSESReturnOfPremium": "",
        "isSSESProduct": "No",
        "SSESSolveOption": "BASE",
        "SSESNatureOfDuties": "",
        "sspNatureOfDuties": "",
        "coverageOption": 0,
        "incomeStartYear": "",
        "premiumOffset": "",
        "desiredDateOfIncomePayout": "",
        "desiredDate": "",
        "solveOption": "",
        "deathBenefitMultiple": "",
        "limitedTerm": "no",
        "deferralAccrualOption": "",
        "secondAnnuitantRiskClass": "",
        "secondAnnuitantSumAssured": "",
        "isJointLife": "",
        "internalRateOfReturn": "no",
        "WPVoucher": "",
        "isWellnessProgram": "",
        "earlyROPPercentage": "",
        "guaranteeAnnuityPeriod": "",
        "proportionOfAnnuityLastSurvivor": "",
        "milestoneAge": "",
        "increasingAnnuityPercentage": "",
        "increasingAnnuityFrequency": "",
        "returnOfPremium": "",
        "returnOfPremiumPercentage": "",
        "isEarlyWealthPlus": "no",
        "returnOfPremium1stDeath": "",
        "returnOfPremium2ndDeath": "",
        "defermentPeriodMonth": "",
        "deferredPeriod": "",
        "survivalBenefitPeriod": "",
        "customerReminderConsent": "No",
        "customerAwareConsent": "No",
        "incomeCover": "",
        "discountSalaried": "no",
        "discountChannel": "no",
        "sumAssuredBooster": "No",
        "applicableDiscount": "",
        "existingCustomerDiscount": "no",
        "stafforSellerDiscount": "no",
        "solutionPremium": "",
        "solutionSumAssured": "",
        "futureIncomePeriod": "",
        "flexiIncomeLevel": "",
        "futureMilestoneLevel": "",
        "isSTARLiteVariant": "",
        "SSESNatureOfDutiesInsured": "",
        "sspNatureOfDutiesInsured": ""
      },
      "ceip": {
        "businessType": "",
        "bdmId": "",
        "enrollerId": "",
        "finderId": ""
      },
      "gstInNumber": ""
    }
  ],
  "medicalInfo": {
    "height": "",
    "familyDetails": [
      {
        "type": "Proposer",
        "familyMember": "",
        "diagnosisAge": "",
        "condition": ""
      },
      {
        "type": "Insured",
        "familyMember": "",
        "diagnosisAge": "",
        "condition": ""
      }
    ],
    "questionSet": [
      {
        "question": "",
        "userSelectedValue": ""
      },
      {
        "question": "",
        "userSelectedValue": ""
      }
    ]
  },
  "employmentDetails": {
    "partiesInformation": [
      {
        "partyType": "Proposer",
        "partyDetails": {
          "annualIncome": "",
          "organisationType": "",
          "industryDetails": {
            "industryInfo": {
              "isPostedOnDefenceLocation": false,
              "isProfessionalDiver": false,
              "isBasedAtOffshore": false,
              "isFlying": false,
              "typeOfAirCraft": "",
              "navyAreaWorking": "",
              "isWorkingInsideMine": false,
              "anyIllnessRelatedToOccupation": false,
              "natureOfRole": "",
              "diveLocation": ""
            }
          },
          "nameOfEmployer": "",
          "jobTitle": "",
          "natureOfDuties": "",
          "placeOfPosting": "",
          "rank": "",
          "branchOfArmedForces": "",
          "areYouInvolvedinhazardousActivities": "",
          "hazardousActivitiesDetails": "",
          "panOrForm60": "",
          "panNumber": "",
          "section139ACheck": "",
          "percentageShare": 0,
          "specifyDutiesType": ""
        }
      },
      {
        "partyType": "Insured",
        "partyDetails": {
          "annualIncome": "",
          "organisationType": "",
          "industryDetails": {
            "industryInfo": {
              "isPostedOnDefenceLocation": false,
              "isProfessionalDiver": false,
              "isBasedAtOffshore": false,
              "isFlying": false,
              "typeOfAirCraft": "",
              "navyAreaWorking": "",
              "isWorkingInsideMine": false,
              "anyIllnessRelatedToOccupation": false,
              "natureOfRole": "",
              "diveLocation": ""
            }
          },
          "nameOfEmployer": "",
          "jobTitle": "",
          "natureOfDuties": "",
          "placeOfPosting": "",
          "rank": "",
          "branchOfArmedForces": "",
          "areYouInvolvedinhazardousActivities": "",
          "hazardousActivitiesDetails": "",
          "panOrForm60": "",
          "panNumber": "",
          "section139ACheck": "",
          "percentageShare": 0
        }
      }
    ],
    "isEIAExist": false,
    "existingEIANumber": "",
    "existingEIANumberRepositoryName": "",
    "isEIANumberExist": false,
    "newEIANumber": "",
    "preferredInsuranceRepositoryName": "",
    "isPoliticallyExposed": false,
    "pepDetails": {
      "isProposerPEP": false,
      "isPayorPep": false,
      "isLIOrNomineePEP": false,
      "isLIPEP": false,
      "isFamilyMemberPEP": false,
      "specifyFamilyMembers": "",
      "politicalExperience": "",
      "affiliationsToPoliticalparty": "",
      "roleInPoliticalParty": "",
      "roleOthers": "",
      "portfolioHandled": "",
      "partyInPower": "",
      "pepEverPostedInForeignOffice": "",
      "foreignOfficeDetails": "",
      "incomeSources": "",
      "pepConvicted": "",
      "convictionDetails": "",
      "isAuthorizedSignatoryPEP": false
    }
  },
  "nomineeDetails": {
    "partyDetails": [
      {
        "salutation": "",
        "fatherOrHusbandName": "",
        "accountForNominee": "",
        "reasonForNomination": "",
        "appointeeDetails": {
          "guardianIsYour": "",
          "appointeeAddress": [
            {
              "addressDetails": {
                "houseNo": "",
                "area": "",
                "landmark": "",
                "city": "",
                "state": "",
                "pinCode": "",
                "country": "",
                "village": ""
              }
            },
            {
              "addressDetails": {
                "houseNo": "",
                "area": "",
                "landmark": "",
                "city": "",
                "state": "",
                "pinCode": "",
                "country": "",
                "village": ""
              }
            }
          ],
          "appointeePhoneDetails": [
            {
              "phoneNumber": "",
              "phoneType": "appointeeMobileNumber"
            }
          ],
          "appointeeBankDetails": {
            "bankDetails": [
              {
                "ifscMicrOption": "appointeeIfsc"
              }
            ]
          },
          "appointeeNationality": {
            "nationality": "indian"
          }
        },
        "percentageShare": 0,
        "nomineeChildName": "",
        "nomineeNationality": {
          "nationality": ""
        },
        "nomineeAddress": [
          {
            "addressDetails": {
              "houseNo": "",
              "area": "",
              "landmark": "",
              "city": "",
              "state": "",
              "pinCode": "",
              "country": "",
              "village": ""
            }
          },
          {
            "addressDetails": {
              "houseNo": "",
              "area": "",
              "landmark": "",
              "city": "",
              "state": "",
              "pinCode": "",
              "country": "",
              "village": ""
            }
          }
        ],
        "nomineePhoneDetails": [
          {
            "phoneNumber": "",
            "phoneType": "nomineeMobileNumber"
          },
          {
            "stdIsdCode": "",
            "phoneType": "nomineeAlternateMobileNo"
          },
          {
            "phoneType": "nomineeAlternateLandlineNo"
          }
        ],
        "nomineeBankDetails": {
          "bankDetails": [
            {
              "ifscMicrOption": "nomineeIfsc"
            }
          ]
        },
        "nomineePanDetails": {
          "isPANExist": false,
          "isPanValidated": false,
          "isDobValidated": false,
          "panOcrFlag": false
        },
        "nomineeIdentityDetails": {
          "isAddressProofSame": false,
          "isChargeableIncome": false,
          "isIncomeExceedLimit": false,
          "isTaxableIncome": false,
          "isItOtherIncome": false,
          "isNRI": false,
          "isApplicableIncome": false,
          "isSecondAnnuitantChargeableIncome": false,
          "isSecondAnnuitantIncomeExceedLimit": false,
          "isSecondAnnuitantTaxableIncome": false,
          "isSecondAnnuitantItOtherIncome": false,
          "isSecondAnnuitantNRI": false,
          "isSecondAnnuitantApplicableIncome": false,
          "isSecondAnnuitantAddressProofSame": false
        },
        "nomineeType": ""
      }
    ]
  },
  "bank": {
    "sameAsBankDetails": "true",
    "chequeDetails": {
      "chequeResponse": false
    },
    "paymentRenewedBy": "",
    "bankDetails": [
      {
        "bankInfoType": "NEFT",
        "bankAccountNumber": "13132434554",
        "accountHolderName": "",
        "micr": "",
        "ifsc": "UTIB0000404",
        "bankName": "HADAPSAR PUNE",
        "bankBranch": "",
        "typeOfAccount": "Savings",
        "secondAnnuitantbankAccountHolderName": "",
        "secondAnnuitantbankAccountIFSC": "",
        "secondAnnuitantbankAccountMICR": "",
        "secondAnnuitantbankName": "",
        "secondAnnuitantbankBranch": "",
        "gstWaiverAccountType": ""
      },
      {
        "bankInfoType": "ECS",
        "bankAccountNumber": "13132434554",
        "accountHolderName": "",
        "micr": "",
        "ifsc": "UTIB0000404",
        "bankName": "HADAPSAR PUNE",
        "bankBranch": "",
        "typeOfAccount": "Savings",
        "bankAccOpeningDate": {
          "$date": "2000-01-01T00:00:00.000Z"
        }
      }
    ],
    "accountForBankDetails": "",
    "secondBankDetails": {
      "bankInfoType": "NEFT",
      "micr": "",
      "ifsc": "",
      "bankName": "",
      "bankBranch": ""
    }
  },
  "form60Details": {
    "identityProofName": "",
    "identityProofNumber": "",
    "identityProofExpiryDate": "",
    "identityProofIssuingAuthority": "",
    "isAddressProofSame": true,
    "addressProofNumber": "",
    "addressProofName": "",
    "addressProofIssuingAuthority": "",
    "detailsOfDontHavePan": "",
    "panAcknowledgementNo": "",
    "isChargeableIncome": false,
    "isIncomeExceedLimit": false,
    "isTaxableIncome": false,
    "isItOtherIncome": false,
    "isNRI": false,
    "isApplicableIncome": false,
    "secondAnnuitantIdentityProof": "",
    "secondAnnuitantIdentityProofNumber": "",
    "secondAnnuitantIdentityProofIssuingAuthority": "",
    "secondAnnuitantAddressProof": "",
    "secondAnnuitantAddressProofNumber": "",
    "secondAnnuitantAddressProofIssuingAuthority": "",
    "secondAnnuitantDetailsOfDontHavePan": "",
    "secondAnnuitantPanAcknowledgementNo": "",
    "isSecondAnnuitantChargeableIncome": false,
    "isSecondAnnuitantIncomeExceedLimit": false,
    "isSecondAnnuitantTaxableIncome": false,
    "isSecondAnnuitantItOtherIncome": false,
    "isSecondAnnuitantNRI": false,
    "isSecondAnnuitantApplicableIncome": false,
    "isSecondAnnuitantAddressProofSame": true
  },
  "ckycDetails": {
    "mothersFirstName": "",
    "mothersLastName": "",
    "doYouHaveCKYCNumber": "No",
    "ckycNumber": "",
    "addressProofType": "",
    "pleaseSpecify": "",
    "addressProofExpiryDate": "",
    "idProofType": "",
    "idProofnumber": "",
    "idProofExpiryDate": "",
    "nriCityOfBirth": ""
  },
  "lifeStyleDetails": [
    {
      "partyType": "Proposer",
      "travelAndAdventure": {
        "doYouParticipateInHazardousActivities": "",
        "travelOrResideAbroad": "",
        "hazardousActivitiesDetails": {
          "parachuting": "",
          "handGliding": "",
          "scubaDiving": "",
          "mountaineering": "",
          "carRacing": "",
          "flying": "",
          "others": "",
          "othersDetails": "",
          "hazardousActivityExtent": ""
        },
        "travelOrResideAbroadDetails": {
          "CICountryTobeVisited": [],
          "city": "",
          "purpose": "",
          "purposeOthers": "",
          "durationOfStay": ""
        }
      },
      "heightAndWeight": {
        "heightMetric": "CM",
        "height": "0",
        "weightChangeReason": "",
        "weightChangeReasonOthers": ""
      },
      "habit": {
        "tobaccoNicotine": {
          "consumeSubstance": "",
          "consumptionDetails": [
            {
              "type": "",
              "frequency": "",
              "quantity": "",
              "numberOfYears": ""
            },
            {
              "type": "",
              "frequency": "",
              "quantity": "",
              "numberOfYears": ""
            }
          ]
        },
        "liquor": {
          "consumeSubstance": "",
          "consumptionDetails": [
            {
              "type": "",
              "frequency": "",
              "quantity": "",
              "numberOfYears": ""
            },
            {
              "type": "",
              "frequency": "",
              "quantity": "",
              "numberOfYears": ""
            }
          ]
        },
        "drugs": {
          "consumeSubstance": "",
          "consumptionDetails": [
            {
              "type": "",
              "frequency": "",
              "quantity": "",
              "numberOfYears": ""
            },
            {
              "type": "",
              "frequency": "",
              "quantity": "",
              "numberOfYears": ""
            }
          ]
        }
      },
      "health": {
        "neverBeenDiagnosedOrTreated": "",
        "diagnosedOrTreatedDetails": {
          "cardio": {
            "highBloodPressure": "",
            "chestPain": "",
            "heartAttack": "",
            "stroke": "",
            "anyOtherHeartCondition": "",
            "specifyDetails": " ",
            "highBloodPressureDetails": {
              "whenWasItDiagnosed": "",
              "medicationDetails": "",
              "followupAfterLastConsultation": "",
              "lastReading": ""
            }
          },
          "hormonal": {
            "highBloodSugar": "",
            "diabetes": "",
            "thyroid": "",
            "anyOtherHormonalDisorder": "",
            "specifyDetails": "",
            "highBloodSugarAndDiabetesDetails": {
              "whenWasItDiagnosed": "",
              "medicationDetails": "",
              "followStrictDiet": "",
              "followupapappAfterLastConsultation": "",
              "lastReading": "",
              "everHadNumbnessOrTingling": ""
            }
          },
          "respiratory": {
            "asthma": "",
            "anyOtherRespiratoryDisorder": "",
            "tuberculosis": "",
            "specifyDetails": "",
            "asthmaDetails": {
              "whenWasItDiagnosed": "",
              "symptomsDetails": "",
              "howOftenSymptomsOccur": "",
              "medicationDetails": "",
              "haveYouTakenSteriods": ""
            },
            "respiratoryDisorderDetails": {
              "whenWasItDiagnosed": "",
              "symptomsDetails": "",
              "howOftenSymptomsOccur": "",
              "medicationDetails": "",
              "haveYouTakenSteriods": ""
            }
          },
          "bloodAndCellular": {
            "cancer": "",
            "tumorAndMalignantGrowth": "",
            "leukemia": "",
            "anyBloodDisorder": "",
            "specifyDetails": ""
          },
          "digestiveAndRegulatory": {
            "stomachOrintestinalDisorder": "",
            "jaundiceOrliverDisorder": "",
            "anyKidneyDisorders": "",
            "specifyDetails": ""
          },
          "mentalAndPsychiatric": {
            "mentalOrPsychiatricAilment": "",
            "nervousSystemDisease": "",
            "specifyDetails": ""
          },
          "neuralOrSkeletalOrMuscular": {
            "anyAilmentOfBonesOrjoints": "",
            "anyDisorderOfSpine": "",
            "anyDisorderOfMuscle": "",
            "anyDisorderOfENT": "",
            "specifyDetails": ""
          },
          "infectiousOrContagious": {
            "hepatitisB": "",
            "hepatitisC": "",
            "hivInfection": "",
            "aidsRelated": "",
            "anySTDDisease": "",
            "anyGynaecologicalDisorder": "",
            "specifyDetails": ""
          },
          "otherMedicalConditions": {
            "anyCongenitalAnomaly": "",
            "anyCongenitalAnomalyDetails": "",
            "otherMedicalCondition": "",
            "otherMedicalConditionDetails": ""
          },
          "hospitalizationAndAbsenceFromWork": {
            "everBeenhospitalized": "",
            "everBeenhospitalizedDetails": "",
            "everBeenAbsentFromWork": "",
            "everBeenAbsentFromWorkDetails": ""
          }
        }
      },
      "familyOrCriminalHistory": {
        "familyDiagnosedWithDiseasesBefore60": "",
        "anyCriminalCharges": "",
        "specifyDetails": "",
        "familyDiagnosedWithDiseasesDetails": [
          {
            "familyMember": "",
            "ageAtDiagnosis": "",
            "medicalProblem": ""
          }
        ]
      },
      "insuranceDetails": {
        "isLICIPolicyExist": false,
        "isLIPolicyRejected": false,
        "liciPolicyDetails": [
          {
            "isLIIssued": false,
            "totalSumAssuredForLI": "",
            "totalSumAssuredForCI": "",
            "nameOfInsuranceCompany": "",
            "policyNumber": "",
            "totalSumAssured": "",
            "policyStatus": "",
            "typeOfPolicy": ""
          }
        ],
        "existingPolDecDefWitAcc": "",
        "existingPolDecDefWitAccDetails": ""
      },
      "parentsDetails": {
        "totalInsuranceCover": "",
        "annualIncome": ""
      }
    },
    {
      "partyType": "Insured",
      "travelAndAdventure": {
        "doYouParticipateInHazardousActivities": "",
        "travelOrResideAbroad": "",
        "hazardousActivitiesDetails": {
          "parachuting": "",
          "handGliding": "",
          "scubaDiving": "",
          "mountaineering": "",
          "carRacing": "",
          "flying": "",
          "others": "",
          "othersDetails": "Other hazardousActivities will be captured",
          "hazardousActivityExtent": ""
        },
        "travelOrResideAbroadDetails": {
          "CICountryTobeVisited": [],
          "city": "",
          "purpose": "",
          "purposeOthers": "",
          "durationOfStay": ""
        }
      },
      "heightAndWeight": {
        "heightMetric": "CM",
        "weightChangeReason": "",
        "weightChangeReasonOthers": ""
      },
      "habit": {
        "tobaccoNicotine": {
          "consumeSubstance": "",
          "consumptionDetails": [
            {
              "type": "",
              "frequency": "",
              "quantity": "",
              "numberOfYears": ""
            },
            {
              "type": "",
              "frequency": "",
              "quantity": "",
              "numberOfYears": ""
            }
          ]
        },
        "liquor": {
          "consumeSubstance": "",
          "consumptionDetails": [
            {
              "type": "",
              "frequency": "",
              "quantity": "",
              "numberOfYears": ""
            },
            {
              "type": "",
              "frequency": "",
              "quantity": "",
              "numberOfYears": ""
            }
          ]
        },
        "drugs": {
          "consumeSubstance": "",
          "consumptionDetails": [
            {
              "type": "",
              "frequency": "",
              "quantity": "",
              "numberOfYears": ""
            },
            {
              "type": "",
              "frequency": "",
              "quantity": "",
              "numberOfYears": ""
            }
          ]
        }
      },
      "health": {
        "neverBeenDiagnosedOrTreated": "",
        "diagnosedOrTreatedDetails": {
          "cardio": {
            "highBloodPressure": "",
            "chestPain": "",
            "heartAttack": "",
            "stroke": "",
            "anyOtherHeartCondition": "",
            "specifyDetails": "",
            "highBloodPressureDetails": {
              "whenWasItDiagnosed": "",
              "medicationDetails": "",
              "followupAfterLastConsultation": "",
              "lastReading": ""
            }
          },
          "hormonal": {
            "highBloodSugar": "",
            "diabetes": "",
            "thyroid": "",
            "anyOtherHormonalDisorder": "",
            "specifyDetails": "",
            "highBloodSugarAndDiabetesDetails": {
              "whenWasItDiagnosed": "",
              "medicationDetails": "",
              "followStrictDiet": "",
              "followupapappAfterLastConsultation": "",
              "lastReading": "",
              "everHadNumbnessOrTingling": ""
            }
          },
          "respiratory": {
            "asthma": "",
            "anyOtherRespiratoryDisorder": "",
            "tuberculosis": "",
            "specifyDetails": "",
            "asthmaDetails": {
              "whenWasItDiagnosed": "",
              "symptomsDetails": "",
              "howOftenSymptomsOccur": "",
              "medicationDetails": "",
              "haveYouTakenSteriods": ""
            },
            "respiratoryDisorderDetails": {
              "whenWasItDiagnosed": "",
              "symptomsDetails": "",
              "howOftenSymptomsOccur": "",
              "medicationDetails": "",
              "haveYouTakenSteriods": ""
            }
          },
          "bloodAndCellular": {
            "cancer": "",
            "tumorAndMalignantGrowth": "",
            "leukemia": "",
            "anyBloodDisorder": "",
            "specifyDetails": ""
          },
          "digestiveAndRegulatory": {
            "stomachOrintestinalDisorder": "",
            "jaundiceOrliverDisorder": "",
            "anyKidneyDisorders": "",
            "specifyDetails": ""
          },
          "mentalAndPsychiatric": {
            "mentalOrPsychiatricAilment": "",
            "nervousSystemDisease": "",
            "specifyDetails": ""
          },
          "neuralOrSkeletalOrMuscular": {
            "anyAilmentOfBonesOrjoints": "",
            "anyDisorderOfSpine": "",
            "anyDisorderOfMuscle": "",
            "anyDisorderOfENT": "",
            "specifyDetails": ""
          },
          "infectiousOrContagious": {
            "hepatitisB": "",
            "hepatitisC": "",
            "hivInfection": "",
            "aidsRelated": "",
            "anySTDDisease": "",
            "anyGynaecologicalDisorder": "",
            "specifyDetails": ""
          },
          "otherMedicalConditions": {
            "anyCongenitalAnomaly": "",
            "anyCongenitalAnomalyDetails": "",
            "otherMedicalCondition": "",
            "otherMedicalConditionDetails": ""
          },
          "hospitalizationAndAbsenceFromWork": {
            "everBeenhospitalized": "",
            "everBeenhospitalizedDetails": "",
            "everBeenAbsentFromWork": "",
            "everBeenAbsentFromWorkDetails": ""
          }
        }
      },
      "familyOrCriminalHistory": {
        "familyDiagnosedWithDiseasesBefore60": "",
        "anyCriminalCharges": "",
        "specifyDetails": "",
        "familyDiagnosedWithDiseasesDetails": [
          {
            "familyMember": "",
            "ageAtDiagnosis": "",
            "medicalProblem": ""
          }
        ]
      },
      "insuranceDetails": {
        "isLICIPolicyExist": false,
        "isLIPolicyRejected": false,
        "liciPolicyDetails": [
          {
            "isLIIssued": false,
            "totalSumAssuredForLI": "",
            "totalSumAssuredForCI": "",
            "nameOfInsuranceCompany": "",
            "policyNumber": "",
            "totalSumAssured": "",
            "policyStatus": "",
            "typeOfPolicy": ""
          }
        ],
        "existingPolDecDefWitAcc": "",
        "existingPolDecDefWitAccDetails": ""
      },
      "parentsDetails": {
        "totalInsuranceCover": "",
        "annualIncome": ""
      }
    }
  ],
  "irp": {
    "willngnssForFinRisk": "",
    "invstmntAppealingUrfolio": "",
    "feelUncmfrtblWhenInvstmntGoDwn": "",
    "dscribeUrSavngshbts": "",
    "recommendedFund": [
      "secures",
      "balanced",
      "highgrowth"
    ],
    "IRPQ1": "",
    "IRPQ2": "",
    "IRPQ3": "",
    "IRPQ4": ""
  },
  "paymentDetails": {
    "receipt": [
      {
        "paymentType": "",
        "paymentReferenceCode": "",
        "proposerNumber": "ryryryryyryryryryr Kumar ",
        "premiumMode": "",
        "isSICheck": false,
        "modeOfPayment": "",
        "isTermAccepted": false,
        "paymentChequeDetails": {
          "chequeNumber": {
            "$numberLong": "0"
          },
          "chequeDate": {
            "$date": "2026-01-07T20:14:47.000Z"
          },
          "chequeAmount": 0,
          "chequePayableAt": "",
          "chequeBankName": "",
          "chequeMicr": {
            "$numberLong": "0"
          }
        },
        "demandDraftDetails": {
          "demandDraftNumber": "",
          "demandDraftDate": {
            "$date": "2026-01-07T20:14:47.000Z"
          },
          "demandDraftAmount": 0,
          "demandDraftPayableAt": "",
          "demandDraftBankName": "",
          "demandDraftMicr": {
            "$numberLong": "0"
          }
        },
        "yblPaymentDetails": {
          "paymentConfirmationCode": "",
          "directDebitDetails": {
            "directDebitRenewals": "no",
            "initialPremium": "",
            "renewalPremium": ""
          }
        },
        "isSIOpted": "false",
        "cardType": ""
      }
    ]
  },
  "additionalFlags": {
    "currentActiveScreen": 2,
    "isIllustrationGenerated": false,
    "isEmailSent": false,
    "isifscMicrValidated": false,
    "isDedupeValidated": "false",
    "screen1": "full",
    "screen2": "half",
    "screen3": "empty",
    "screen4": "empty",
    "screen5": "empty",
    "screen6": "empty",
    "isPayorDiffFromPropser": false,
    "isIllustrationGeneratedOnScreen2": false,
    "isPaymentDone": false,
    "preIssuanceVerificationNumber": "",
    "requestSource": "MPRO",
    "agentKnowsProposerSince": "",
    "agentKnowsProposerUnitType": "",
    "isMaxEmp": "",
    "proposerPreviousPolicyNumber": "",
    "isPersonalInfoEdited": false,
    "isPermAddressEdited": false,
    "isCommAddressEdited": false,
    "isAddressProofTypeEdited": "No",
    "yblNEFTModifiedUi": "",
    "isdedupeadressEdited": false,
    "isRenewelPaymentDone": false,
    "isteleMERStatus": "No",
    "isvideoMERStatus": "No",
    "isteleMERFlag": false,
    "isvideoMERFlag": false,
    "isteleMERProposerFlag": false,
    "isvideoMERProposerFlag": false,
    "aadhaarEncryptionStatus": "",
    "aadhaarDocStatus": "fail",
    "resendLink": "",
    "isRaCommunicationSent": false,
    "sellerSegment": "Y",
    "photoVerified": false,
    "stpIdDobproof": false,
    "stpAddressProf": false,
    "stpNach": false,
    "cancelledChequeNeft": false,
    "billdeskRetryCount": 0,
    "posvRetriggeredforProposer": "N",
    "isProposerEkycVerified": "",
    "isInsurerEkycVerified": "",
    "isPayorEkycVerified": "",
    "proposerEkycSkip": "No",
    "accountAggregatorEkycSkip": "No",
    "insuredEkycSkip": "No",
    "payorEkycSkip": "No",
    "isYBLGenieSubStatusCall": false,
    "isIibCalledForProposer": "No",
    "isIibCalledForInsurer": "No",
    "isAccidentalDeathBenefit": false,
    "isPasaTermProductApplicable": false,
    "isPasaSavingProductApplicable": false,
    "selectedActivePolicy": "",
    "isSecondBankAsSameFirstCheck": false,
    "agentFraudCheckDetails": {
      "source": "",
      "panMatched": "",
      "dobMatched": "",
      "emailMatched": "",
      "mobileMatched": "",
      "isAgentSelf": "",
      "agentFraudIdentified": "",
      "agentFraudCheckSkip": "",
      "requestTimestamp": "",
      "responseTimestamp": "",
      "serviceStatus": "",
      "auditRequestId": "",
      "sellerContactDeclaration": ""
    },
    "nominee1": {
      "agentFraudCheckDetails": {
        "source": "",
        "panMatched": "",
        "dobMatched": "",
        "emailMatched": "",
        "mobileMatched": "",
        "isAgentSelf": "",
        "agentFraudIdentified": "",
        "agentFraudCheckSkip": "",
        "requestTimestamp": "",
        "responseTimestamp": "",
        "serviceStatus": "",
        "auditRequestId": "",
        "sellerContactDeclaration": "",
        "firstName": "",
        "lastName": "",
        "panNumber": "",
        "dob": "",
        "phoneNumber": "",
        "email": ""
      }
    },
    "nominee2": {
      "agentFraudCheckDetails": {
        "source": "",
        "panMatched": "",
        "dobMatched": "",
        "emailMatched": "",
        "mobileMatched": "",
        "isAgentSelf": "",
        "agentFraudIdentified": "",
        "agentFraudCheckSkip": "",
        "requestTimestamp": "",
        "responseTimestamp": "",
        "serviceStatus": "",
        "auditRequestId": "",
        "sellerContactDeclaration": "",
        "firstName": "",
        "lastName": "",
        "panNumber": "",
        "dob": "",
        "phoneNumber": "",
        "email": ""
      }
    },
    "nominee3": {
      "agentFraudCheckDetails": {
        "source": "",
        "panMatched": "",
        "dobMatched": "",
        "emailMatched": "",
        "mobileMatched": "",
        "isAgentSelf": "",
        "agentFraudIdentified": "",
        "agentFraudCheckSkip": "",
        "requestTimestamp": "",
        "responseTimestamp": "",
        "serviceStatus": "",
        "auditRequestId": "",
        "sellerContactDeclaration": "",
        "firstName": "",
        "lastName": "",
        "panNumber": "",
        "dob": "",
        "phoneNumber": "",
        "email": ""
      }
    },
    "appointee1": {
      "agentFraudCheckDetails": {
        "source": "",
        "panMatched": "",
        "dobMatched": "",
        "emailMatched": "",
        "mobileMatched": "",
        "isAgentSelf": "",
        "agentFraudIdentified": "",
        "agentFraudCheckSkip": "",
        "requestTimestamp": "",
        "responseTimestamp": "",
        "serviceStatus": "",
        "auditRequestId": "",
        "sellerContactDeclaration": "",
        "firstName": "",
        "lastName": "",
        "panNumber": "",
        "dob": "",
        "phoneNumber": "",
        "email": ""
      }
    },
    "appointee2": {
      "agentFraudCheckDetails": {
        "source": "",
        "panMatched": "",
        "dobMatched": "",
        "emailMatched": "",
        "mobileMatched": "",
        "isAgentSelf": "",
        "agentFraudIdentified": "",
        "agentFraudCheckSkip": "",
        "requestTimestamp": "",
        "responseTimestamp": "",
        "serviceStatus": "",
        "auditRequestId": "",
        "sellerContactDeclaration": "",
        "firstName": "",
        "lastName": "",
        "panNumber": "",
        "dob": "",
        "phoneNumber": "",
        "email": ""
      }
    },
    "appointee3": {
      "agentFraudCheckDetails": {
        "source": "",
        "panMatched": "",
        "dobMatched": "",
        "emailMatched": "",
        "mobileMatched": "",
        "isAgentSelf": "",
        "agentFraudIdentified": "",
        "agentFraudCheckSkip": "",
        "requestTimestamp": "",
        "responseTimestamp": "",
        "serviceStatus": "",
        "auditRequestId": "",
        "sellerContactDeclaration": "",
        "firstName": "",
        "lastName": "",
        "panNumber": "",
        "dob": "",
        "phoneNumber": "",
        "email": ""
      }
    },
    "replacementSale": "N",
    "policySplitting": "N",
    "selfDeclerationConsent": false,
    "psmApiStatus": "true",
    "isCPDAPIValidated": false,
    "isCoiApplicable": false,
    "isYblTelesalesCase": false,
    "isEducationPresent": false,
    "isOccupationPresent": false,
    "ebcc": false,
    "userDocumentSubmittedAtUiInThanos": false,
    "isSecondAnnuitantPEP": false,
    "annuitantReflexive": "",
    "posEmailStatus": false,
    "gstWaiverRequired": "",
    "isEpfoMobChange": true,
    "altfinEnqStage4Status": "",
    "isHealthApplicable": false,
    "panChangeStatus": false,
    "isPhotoSupress": false,
    "isRaIdPresent": false,
    "utmCode": "",
    "journeyIdentifer": "",
    "isFalconProduct": "No",
    "isCkycNumberVerified": false,
    "financialDocumentSelected": "",
    "otherDocument": "",
    "isInstaCOIProductEligible": false,
    "isReplacementSaleApiCalled": "N",
    "isNpsJourney": "",
    "isNpsJourneyInitiated": "",
    "isCSFBChannel": "No",
    "isNeedToEnableResendButton": false,
    "agencyContest": "",
    "isCkycApiTrigerred": false,
    "mproJourneyDataPrefilledWith": "",
    "isProspectiveYBLCustomer": false,
    "disableScreen6ForAgenyYblPOS": "No",
    "pennyDropConsent": "No",
    "defenceChannel": "no",
    "isNriEmodelYBLCustomer": false,
    "new2YblNoPan": false,
    "isEkycDobVerified": "No",
    "aadhaarDob": "",
    "posSellerLifeHealthDisclosure": "",
    "vernacularDeclaration": {
      "vernacularAccepted": "No",
      "vernacularFirstName": "",
      "vernacularLastName": "",
      "vernacularAddress": ""
    },
    "disabilityDeclaration": {
      "declarantFirstName": "",
      "declarantLastName": "",
      "declarantMobileNumber": "",
      "declarantRelationshipWithProposer": "",
      "declarantAddress": "",
      "disabilityDeclarationFlag": "No",
      "declarantOtpValidated": "No",
      "declarantRelationshipWithOthers": "",
      "disabilityQuestion": "",
      "disabilityType": "",
      "otherDisabilityDetails": "",
      "disabilityPercentage": ""
    },
    "journeyType": "J3",
    "sourceChannel": "",
    "whatsappConsent": "",
    "isPanModifiedForThanos": false,
    "showInterimOption": false,
    "isInterimSelected": "No",
    "isPtfPayment": "no",
    "emailSMSConsent": false,
    "resendCount": "0",
    "insuredResendCount": "0",
    "showCovidQuesOnPosv": "N",
    "isCipQuestionMarkedYes": false,
    "isNJChannel": false,
    "documentSharingApplicableToRA": false,
    "isExistingCustomerDiscount": "No",
    "isDiscrepancyPosvReTriggered": false,
    "leadMessage": "",
    "isBankDetailsReEdited": false,
    "isPhysicalAxisCase": "No",
    "isPennyDropApplicable": false,
    "citiBankComConsent": false,
    "dolphinRepushCount": 0,
    "isCaseOpenedFromDashboard": false,
    "isAgent360CalledForCampaignId": "",
    "isFalconJourney": "No",
    "isPaymentConfirmation": false,
    "isShriramFinance": "false",
    "existingPolicyMaxOrNot": "",
    "isSuperAnnuationFundPolicy": "",
    "clientId": "",
    "clientIdValidated": false,
    "disableCatAxisClientId": "Y",
    "paymentFirstConsent": false,
    "upfrontPaymentConsent": "",
    "currentMonthSelected": false,
    "isCs2LinkTriggerred": "No",
    "isBSJourneyTriggered": "No",
    "isITRJourneyTriggered": "No",
    "upfrontpaymentconsentsys": "",
    "isPaymentLastEnabled": "",
    "isMmmaPolicyStatusWip": "",
    "enableNatureOfDutiesForAll": "Y",
    "isInterimPaymentLast": "",
    "journeyProgressMode": "",
    "journeyFlowType": "",
    "spApproverName": "",
    "isLinkTriggeredToSp": false,
    "isTMBChannel": false,
    "isUjjivanChannel": false,
    "isSIBChannel": "No",
    "isNewBankOrCaJourney": false,
    "formCFeatureEnabled": "N",
    "isCatChannel": "Y",
    "isSspSwissReCase": "N",
    "isDCBChannel": false,
    "isMotilalOswal": false,
    "isMahindraChannel": "NO",
    "appointeeIfscMicrOption": "",
    "ifscMicrOption": "",
    "secondAnnuitantIfscMicrOption": "",
    "nomineeIfscMicrOption": "",
    "renewalIfscMicrOption": "",
    "ocrDocumentScreen3": "",
    "isAAJourneyCompleted": false,
    "isInsuredPOSVReTriggered": false,
    "insuredPosvJourneyFlag": "FALSE",
    "companyDepartmentName": "",
    "companyDepartmentLocation": "",
    "isECSRenewalPaymentDone": false,
    "showECSOption": "",
    "isDhuCase": "Y",
    "isCSBChannel": false,
    "isIvcDiscrepancyCase": false,
    "isProposerEkycDobVerified": false,
    "isInsurerEkycDobVerified": false,
    "isPayorEkycDobVerified": false,
    "paymentStatusPopupFlag": false,
    "currAddProofPayor": "NA",
    "isPanValidatedPayor": false,
    "stpNachPayor": "NA",
    "currAddProofPayorSource": "NA",
    "isPanValidatedPayorSource": "NA",
    "isDobValidatedInsuredSource": "NA",
    "isVideoPOSV": "NA",
    "OASDocRequired": "NA",
    "mostImportantDocumentTMB": "NA",
    "isProposerEcsRenewalMode": "NA",
    "isPayorEcsRenewalMode": "NA",
    "proposersSpouseIncomeProof": "NA",
    "payorIncomeProofValidated": "NA",
    "liveSelfieInSPOSV": "NA",
    "rakshakDocument": "NA",
    "isFTINIndian": "NA",
    "isNRI": "NA",
    "isBusinessInsurance": "NA",
    "isPhysicalJourney": "NA",
    "mwpaApplicability": "NA",
    "dedupe": "False",
    "shorterJourneyFlag": "No",
    "atrFlag": "N",
    "isPosvFirstCall": "N",
    "selectedEkycDocument": "",
    "isProposerOcrConsentGiven": "",
    "stpAddressProfSource": "NA",
    "isPanValidatedSource": "NA",
    "stpIdDobproofSource": "NA",
    "reasonForSS": "",
    "otherReasonForSS": "",
    "proceedByFifthScreenButton": false,
    "basbaConsent": "N",
    "paymentModeOnThirdScreen": "",
    "renewalPaymentModeOnThirdScreen": "",
    "siWipForAxis": "",
    "siWipForNonAxis": "",
    "isPaymentLastEnabledWip": "",
    "initialPaymentTimerLeft": "",
    "renewalPaymentTimerLeft": "",
    "initialPaymentLinkOpened": "",
    "renewalPaymentLinkOpened": "",
    "sifeatureflagfnr": "",
    "checkIfAxisCase": false,
    "showSiIntial": "",
    "policyPurchasedAfterConsent": false
  },
  "underwritingServiceDetails": {
    "medicalShedulingDetails": {
      "visitType": "",
      "labDetails": {
        "labId": "",
        "name": "",
        "address": ""
      },
      "labIndex": ""
    }
  },
  "csgDetails": {
    "CSGCategory": ""
  },
  "bancaDetails": {
    "customerId": "NTE2OTY3OTc5",
    "bancaId": "9555972313",
    "bankAccountOpeningDate": "01-03-2000",
    "isCountryCodeIndian": "Y",
    "ekyc": "Y",
    "ukyc": "Y",
    "customerSegment": "PRIME",
    "customerClassification": "SBNRE",
    "leadId": "972241581585",
    "addonType": "",
    "maxLifeRegisteredState": "",
    "isPANAvailable": false,
    "isMICRAvailable": false,
    "referenceId": "",
    "primaryId": {
      "$numberLong": "0"
    },
    "crmBancaCustomerDetails": {
      "crmBankBranchName": "HADAPSAR PUNE",
      "crmtitle": "Mr",
      "crmCustomerFirstName": "ryryryryyryryryryr",
      "crmCustomerMiddleName": " ",
      "crmCustomerLastName": "Kumar",
      "crmAccountNo": "13132434554"
    },
    "freeText4": "50022770388857",
    "specifiedPersonCode": "SP0069181927",
    "agentRole": "ASM",
    "constitutionCode": "1",
    "offerName": "PASAR11",
    "crmStatus": "5",
    "lastSpCode": "SP0069181927",
    "title": "Mr",
    "ckyc": "50022770388857",
    "leadSourceOption": "",
    "gstWaiverRequired": "yes",
    "selectedAccNumber": ""
  },
  "salesStoriesProductDetails": {
    "primaryTransactionId": {
      "$numberLong": "0"
    },
    "secondaryMongoId": "",
    "secondaryTransactionId": {
      "$numberLong": "0"
    },
    "isSalesProduct": "no"
  },
  "pasaDetails": {
    "isPasaEligible": "",
    "isPasaApplied": "",
    "pasaQuestions": {
      "pasaQ1": "",
      "pasaQ2": "",
      "pasaQ3": "",
      "pasaQ4": ""
    },
    "sumAssured": 0,
    "uniqueId": "",
    "custId": "",
    "offerType": "",
    "pasaCategory1": "",
    "categoryCode1": "",
    "pasaCategory2": "",
    "categoryCode2": "",
    "premium": "",
    "pasaProducts": [
      {
        "productId": "",
        "productName": "",
        "productType": "",
        "premiumBackOption": "",
        "lifeStageEventBenefit": "",
        "deathBenefit": ""
      }
    ]
  },
  "psmDetails": {
    "isExistingLICover": "Yes",
    "existingLICover": "",
    "riskAppetite": "Medium",
    "recommendedProducts": [
      "Max Life Saral Jeevan Bima",
      "Max Life Cancer Insurance Plan",
      "Forever Young Pension Plan",
      "Max Life Life Perfect Partner Super",
      "Max Life Fast Track Super Plan",
      "Max Life Monthly Income Advantage Plan",
      "Max Life Platinum Wealth Plan",
      "Max Life Future Genius Education Plan",
      "Max Life Savings Advantage Plan",
      "Max Life Flexi Wealth Plus Plan",
      "Max Life Smart Wealth Plan",
      "Max Life Saral Pension Plan",
      "Max Life Smart Secure Plus Plan",
      "Max Life Smart Wealth Income Plan",
      "Max Life Flexi Wealth Plus Plan",
      "Max Life Smart Wealth Advantage guarantee Plan"
    ]
  },
  "neoAdditionalDetails": {
    "crmLeadId": "",
    "influenceChannel": "",
    "eqouteNumber": ""
  },
  "thanosDolphinIntegrationEnabled": false,
  "physicalJourneyDetails": {
    "customerSignDate": "",
    "customerSignLocation": "",
    "sellerSignDate": "",
    "sellerSignLocation": "",
    "applicationReceivedDate": "",
    "illiterateAndVernacularDeclaration": "",
    "sellerId": ""
  },
  "brmsFieldConfigurationDetails": {
    "productRestricted": "",
    "productRestrictMessage": "",
    "campaignID": "",
    "campaignLocation": "",
    "custIdDataType": "",
    "custIdLength": "",
    "customerID": "",
    "form1": "",
    "form2": "",
    "formC": "",
    "digitalJourney": "",
    "isBRMSApiApplicable": "",
    "pOSPJourney": "",
    "indianNationaility": "",
    "nRInationality": "",
    "lEChannelCode": "",
    "lEChannelName": "",
    "productAnnualMode": "",
    "productMinPrem": "",
    "productModeCode": "",
    "productMonthlyMode": "",
    "productQuarterlyMode": "",
    "productSemiMode": "",
    "cashOption": "",
    "chequeOption": "",
    "dDOption": "",
    "directDebitMannualOption": "",
    "onlineOption": "",
    "renewalDirectDebit": "",
    "renewalEnach": "",
    "renewalCheque": "",
    "renewalECS": "",
    "splitPayment": "",
    "medicalScheduling": "",
    "dNDOption": "",
    "sellerDeclarationonMob": "",
    "auditRequestId": "",
    "serviceStatus": "",
    "campaignIDDataType": "",
    "campaignIDLength": "",
    "campaignLocationDataType": "",
    "campaignLocationLength": "",
    "jvBranding": "",
    "pasaEnablement": "",
    "isPasaHashingEnabled": "",
    "PasaTermProducts": [],
    "PasaSavingProducts": [],
    "productMinPremAnnual": "",
    "productMinPremSemi": "",
    "productMinPremQuarterly": "",
    "productMinPremMonthly": "",
    "refIdDataType": "",
    "refIdLength": "",
    "referenceId": "",
    "singlePremiumApplicable": "",
    "whatsappConsent": "",
    "formCSchemeA": "",
    "formCSchemeB": "",
    "nosellerdeclaration": ""
  },
  "diyBrmsFieldConfigurationDetails": {
    "utmBasedLogic": {
      "staticAgentId": "",
      "partnerLogoDisplay": "",
      "advisorId": "",
      "leSecondaryChannel": "",
      "journeyType": "",
      "leChannelName": "",
      "continueJourneyUrl": "",
      "channelCode": "",
      "leChannelCode": "",
      "productEnabled": "",
      "renewalType": "",
      "customerDataFetch": "",
      "paymentMode": "",
      "formType": "",
      "jvRemoval": "",
      "pasaEnablement": "",
      "isPasaHashingEnabled": "",
      "PasaTermProducts": [],
      "PasaSavingProducts": [],
      "advisorIdVerbiage": "",
      "journeyTypeProductCode": "",
      "posvApplicability": "",
      "paymentType": "",
      "smsDailyLimit": "",
      "smsInstanceLimit": "",
      "coolDownPeriod": "",
      "sourceChannel": "",
      "diyJourneyType": "",
      "dolphinPushChannelCode": "",
      "influencerChannel": "",
      "psmGrid": "",
      "productCommissionability": "",
      "advisoridviacampaignid": "",
      "whatsappConsent": "",
      "nosellerdeclaration": ""
    }
  },
  "coherentIllustrationResponse": {},
  "_class": "com.mli.mpro.proposal.models.ProposalDetails"
}




db.proposalDetails.findOne(
  {"applicationDetails.transactionId": 2000111200},
  {"sourcingDetails.specifiedPersonDetails.isSpJourneyCompleted": 1, "applicationDetails.transactionId": 1}
)
