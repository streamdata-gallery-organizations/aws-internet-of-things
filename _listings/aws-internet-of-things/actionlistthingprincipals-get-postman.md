{
  "info": {
    "name": "AWS Internet of Things API List Thing Principals",
    "_postman_id": "8390d455-cb20-44e0-8011-542e47085818",
    "description": "Lists the principals associated with the specified thing.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Certificate Transfers",
      "item": [
        {
          "id": "afe8f626-4a23-46c6-abbd-968a7a1e5bd7",
          "name": "acceptCertificateTransfer",
          "request": {
            "url": "http://example.com/api/?Action=AcceptCertificateTransfer?certificateId=certificateId&setAsActive=setAsActive",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Accepts a pending certificate transfer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da0869bb-2a8b-4b73-8b0e-5ca915d247e7"
            }
          ]
        },
        {
          "id": "b0ff0b95-e4ca-4850-9ecc-9a995df85a94",
          "name": "cancelCertificateTransfer",
          "request": {
            "url": "http://example.com/api/?Action=CancelCertificateTransfer?certificateId=certificateId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels a pending transfer for the specified certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2e5268c4-54d8-49f6-a376-4afe2fda50e8"
            }
          ]
        }
      ]
    },
    {
      "name": "Principal Policies",
      "item": [
        {
          "id": "f3d73b01-8b98-4e87-8270-6b48992e1f6c",
          "name": "attachPrincipalPolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachPrincipalPolicy?policyName=policyName&principal=principal",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified policy to the specified principal (certificate or other credential)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09153466-0ec1-4de9-bcc5-eb4233491c72"
            }
          ]
        },
        {
          "id": "bd458e3c-3d3f-4b96-a048-a80fc08dd008",
          "name": "detachPrincipalPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachPrincipalPolicy?policyName=policyName&principal=principal",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified policy from the specified certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "16177bb4-c3b9-4ef3-aca2-bd86734d432e"
            }
          ]
        },
        {
          "id": "a6c35cb3-d99a-4c1b-a03d-5b19e789d7fd",
          "name": "listPrincipalPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListPrincipalPolicies?ascendingOrder=ascendingOrder&marker=marker&pageSize=pageSize&principal=principal",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the policies attached to the specified principal."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2a64e105-8725-4c92-bc94-1005cda6dbba"
            }
          ]
        }
      ]
    },
    {
      "name": "Thing Principals",
      "item": [
        {
          "id": "4109a8bf-3303-4a99-b0bf-b80f14d81176",
          "name": "attachThingPrincipal",
          "request": {
            "url": "http://example.com/api/?Action=AttachThingPrincipal?principal=principal&thingName=thingName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified principal to the specified thing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59c36b6d-8de3-4ce4-bd1d-0c3868c93ee3"
            }
          ]
        },
        {
          "id": "90862b18-4ed5-4411-a98b-6750e1488ab1",
          "name": "detachThingPrincipal",
          "request": {
            "url": "http://example.com/api/?Action=DetachThingPrincipal?principal=principal&thingName=thingName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches the specified principal from the specified thing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "14129e8e-90cf-4969-9c26-a01bdf234291"
            }
          ]
        },
        {
          "id": "de9114db-4899-4190-9675-cfea454a502b",
          "name": "listThingPrincipals",
          "request": {
            "url": "http://example.com/api/?Action=ListThingPrincipals?thingName=thingName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the principals associated with the specified thing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b01726b1-34de-4792-a128-5d2c01c095b8"
            }
          ]
        }
      ]
    },
    {
      "name": "Certificates",
      "item": [
        {
          "id": "f67416d6-e8ea-4d6e-9600-988c120186a6",
          "name": "createCertificateFromCsr",
          "request": {
            "url": "http://example.com/api/?Action=CreateCertificateFromCsr?certificateSigningRequest=certificateSigningRequest&setAsActive=setAsActive",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an X."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ba725eb-6eb0-4704-bdf6-dd8b09abe069"
            }
          ]
        },
        {
          "id": "348f2468-e04b-48d4-a847-c6cc641c16e3",
          "name": "deleteCertificate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteCertificate?certificateId=certificateId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b2c5c89b-a724-4ffd-bc7d-c501cf3940d3"
            }
          ]
        },
        {
          "id": "d6e91b94-32ca-47fc-9544-2cd87445a053",
          "name": "describeCertificate",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCertificate?certificateId=certificateId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the specified certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ca4d08f-1505-4efc-9a6a-a54447e51b7f"
            }
          ]
        },
        {
          "id": "631ae381-1ac9-43b0-8737-c1921c8b83b8",
          "name": "listCertificates",
          "request": {
            "url": "http://example.com/api/?Action=ListCertificates?ascendingOrder=ascendingOrder&marker=marker&pageSize=pageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the certificates registered in your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "985f425a-980e-409c-9e2c-a0496d8180d3"
            }
          ]
        },
        {
          "id": "9dad9a8a-7261-40d2-bfe1-23709cbd0ee2",
          "name": "listOutgoingCertificates",
          "request": {
            "url": "http://example.com/api/?Action=ListOutgoingCertificates?ascendingOrder=ascendingOrder&marker=marker&pageSize=pageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists certificates that are being transfered but not yet accepted."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15c53de2-a66f-4aeb-b127-70d95a418dee"
            }
          ]
        }
      ]
    },
    {
      "name": "Keys And Certificates",
      "item": [
        {
          "id": "4b919d5a-fb89-486e-b73f-157ef0842057",
          "name": "createKeysAndCertificate",
          "request": {
            "url": "http://example.com/api/?Action=CreateKeysAndCertificate?setAsActive=setAsActive",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a 2048-bit RSA key pair and issues an X."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8839f133-5137-4888-bd8e-84744a2d55c4"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "e7767a83-b1b7-4c2e-a179-0e94d2a8403c",
          "name": "createPolicy",
          "request": {
            "url": "http://example.com/api/?Action=CreatePolicy?policyDocument=policyDocument&policyName=policyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an AWS IoT policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4a9590d-c855-454a-ae6a-e06179b087c3"
            }
          ]
        },
        {
          "id": "3480f880-46fa-4aac-b277-d73d7dc59fb6",
          "name": "createPolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=CreatePolicyVersion?policyDocument=policyDocument&policyName=policyName&setAsDefault=setAsDefault",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new version of the specified AWS IoT policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b414fa30-2f7d-4960-9ea3-d6479a2a85fb"
            }
          ]
        },
        {
          "id": "1fb95b31-e19b-4b32-907e-a18bdeec2377",
          "name": "deletePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicy?policyName=policyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7784aa56-0735-43b1-b2a9-e7389ec1a9bb"
            }
          ]
        },
        {
          "id": "0581da98-3d9b-41bf-85be-842686fca04f",
          "name": "deletePolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicyVersion?policyName=policyName&policyVersionId=policyVersionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified version of the specified policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9cf11efc-c8c8-4f19-873f-c12c52c900dc"
            }
          ]
        },
        {
          "id": "6be1197d-28f9-4b15-a336-1302892121b3",
          "name": "getPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetPolicy?policyName=policyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the specified policy with the policy document of the default version."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "768265f4-5659-443f-912a-9f639f8bbdb4"
            }
          ]
        },
        {
          "id": "79cf209c-71e8-4f8c-abc6-418a895c8440",
          "name": "getPolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=GetPolicyVersion?policyName=policyName&policyVersionId=policyVersionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the specified policy version."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f1080af1-7e90-4762-a155-f347b39157ac"
            }
          ]
        },
        {
          "id": "e0795808-ef32-4930-8d1e-6d1e2eab2d96",
          "name": "listPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListPolicies?ascendingOrder=ascendingOrder&marker=marker&pageSize=pageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists your policies."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15c0fd15-9f69-44f4-b4e1-16d94de5d030"
            }
          ]
        }
      ]
    },
    {
      "name": "Things",
      "item": [
        {
          "id": "20fc1772-45c3-4273-b41f-f34eebd61515",
          "name": "createThing",
          "request": {
            "url": "http://example.com/api/?Action=CreateThing?attributePayload=attributePayload&thingName=thingName&thingTypeName=thingTypeName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a thing record in the thing registry."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6fa2026-eea4-4c45-a4c5-6b5fa100d457"
            }
          ]
        },
        {
          "id": "926a7699-2bde-45ad-b5fc-81528301d74a",
          "name": "deleteThing",
          "request": {
            "url": "http://example.com/api/?Action=DeleteThing?expectedVersion=expectedVersion&thingName=thingName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified thing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "662cbc13-719a-47c3-86a2-2a080408b4d2"
            }
          ]
        },
        {
          "id": "257259f5-70e7-419c-a12d-c03e2ae6975d",
          "name": "describeThing",
          "request": {
            "url": "http://example.com/api/?Action=DescribeThing?thingName=thingName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the specified thing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92a3eef9-1961-425b-a639-0f568c270513"
            }
          ]
        }
      ]
    },
    {
      "name": "Thing Types",
      "item": [
        {
          "id": "49cf4ad5-71f3-48ac-b4d9-68c846f69875",
          "name": "createThingType",
          "request": {
            "url": "http://example.com/api/?Action=CreateThingType?thingTypeName=thingTypeName&thingTypeProperties=thingTypeProperties",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new thing type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "315ea393-0dcd-4b87-a11c-de1edb30b512"
            }
          ]
        },
        {
          "id": "d7f3a3d4-9a94-4391-9330-f47b1b5582d5",
          "name": "deleteThingType",
          "request": {
            "url": "http://example.com/api/?Action=DeleteThingType?thingTypeName=thingTypeName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified thing type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9a534de-7440-4a8d-9c0e-9eec3fece0a4"
            }
          ]
        },
        {
          "id": "a0e5dfd0-701f-4d46-b5b8-1bbfddddcffe",
          "name": "deprecateThingType",
          "request": {
            "url": "http://example.com/api/?Action=DeprecateThingType?thingTypeName=thingTypeName&undoDeprecate=undoDeprecate",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deprecates a thing type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d8c36b3f-b1ef-4c61-9310-28ed841a3450"
            }
          ]
        },
        {
          "id": "05e75783-6dd4-46bd-b674-2e22957d1165",
          "name": "describeThingType",
          "request": {
            "url": "http://example.com/api/?Action=DescribeThingType?thingTypeName=thingTypeName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the specified thing type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "537ea1d5-28e5-4b98-8842-e7e5fa2360bb"
            }
          ]
        }
      ]
    },
    {
      "name": "Topic Rules",
      "item": [
        {
          "id": "545038d5-6dfc-4a7b-abd1-5a1a100c4a41",
          "name": "createTopicRule",
          "request": {
            "url": "http://example.com/api/?Action=CreateTopicRule?ruleName=ruleName&topicRulePayload=topicRulePayload",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9069c26b-324e-424a-aef9-af7e85af6b8e"
            }
          ]
        },
        {
          "id": "1be9250a-49ce-4d74-9ecb-5737a13d9891",
          "name": "deleteTopicRule",
          "request": {
            "url": "http://example.com/api/?Action=DeleteTopicRule?ruleName=ruleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "97191c3f-ed2a-4045-971a-0f2f7724af7d"
            }
          ]
        },
        {
          "id": "8abff606-55bf-478c-82d8-23e71d5ad3c6",
          "name": "disableTopicRule",
          "request": {
            "url": "http://example.com/api/?Action=DisableTopicRule?ruleName=ruleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables the specified rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "330b4baa-fd0c-4a8e-ae66-659c98c423e0"
            }
          ]
        },
        {
          "id": "21802b5a-2517-4f11-8bc9-d4bcdbbf4e80",
          "name": "enableTopicRule",
          "request": {
            "url": "http://example.com/api/?Action=EnableTopicRule?ruleName=ruleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables the specified rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4899c15d-f9df-4ee1-9f68-0b363ace6fec"
            }
          ]
        },
        {
          "id": "94c01474-bdbd-4608-a979-8bbf3dd33c7b",
          "name": "getTopicRule",
          "request": {
            "url": "http://example.com/api/?Action=GetTopicRule?ruleName=ruleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the specified rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84ddc8f8-6a46-4edb-8b90-24f2bf2fa931"
            }
          ]
        }
      ]
    },
    {
      "name": "CA Certificates",
      "item": [
        {
          "id": "9536f745-a010-41fe-a416-2adf2e8647ba",
          "name": "deleteCACertificate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteCACertificate?certificateId=certificateId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a registered CA certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "22f551c6-30d4-449b-b6bf-cc3d384faa24"
            }
          ]
        },
        {
          "id": "fa783eeb-3a0a-4e2c-8771-170cf3a78b5d",
          "name": "describeCACertificate",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCACertificate?certificateId=certificateId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes a registered CA certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f723ade0-eb23-4291-aeb6-bc691fe5f299"
            }
          ]
        },
        {
          "id": "e7efe701-7c32-4f80-84f0-fd1c92bc4a7b",
          "name": "listCACertificates",
          "request": {
            "url": "http://example.com/api/?Action=ListCACertificates?ascendingOrder=ascendingOrder&marker=marker&pageSize=pageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the CA certificates registered for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9fd8ecfd-5415-4dcd-878a-99db04ec2c1a"
            }
          ]
        },
        {
          "id": "234187e9-b5ca-4acd-981b-cecf0310ccbc",
          "name": "listCertificatesByCA",
          "request": {
            "url": "http://example.com/api/?Action=ListCertificatesByCA?ascendingOrder=ascendingOrder&caCertificateId=caCertificateId&marker=marker&pageSize=pageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the device certificates signed by the specified CA certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9345df5-3d84-4216-9a81-076f69c1a996"
            }
          ]
        }
      ]
    },
    {
      "name": "Registration Codes",
      "item": [
        {
          "id": "395bd0d5-41aa-4a1d-b405-63b6c9a6385e",
          "name": "deleteRegistrationCode",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRegistrationCode",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a CA certificate registration code."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "177d4706-adda-4a04-ba25-2cf9393247d2"
            }
          ]
        },
        {
          "id": "8319879b-6e61-4a5b-be7a-9fa55809c9c1",
          "name": "getRegistrationCode",
          "request": {
            "url": "http://example.com/api/?Action=GetRegistrationCode?registrationCode=registrationCode",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a registration code used to register a CA certificate with AWS IoT."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ed08e38-b93a-4904-936f-532f2bde89c2"
            }
          ]
        }
      ]
    },
    {
      "name": "Endpoints",
      "item": [
        {
          "id": "4a65ba45-bee8-4de9-a9c3-2a27ab43acf9",
          "name": "describeEndpoint",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEndpoint?endpointAddress=endpointAddress",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a unique endpoint specific to the AWS account making the call."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0b69040-86c8-4e93-9a3e-d8172bd9ed02"
            }
          ]
        }
      ]
    },
    {
      "name": "Logging Options",
      "item": [
        {
          "id": "e637a895-0793-442a-a9ec-756afaeb91a6",
          "name": "getLoggingOptions",
          "request": {
            "url": "http://example.com/api/?Action=GetLoggingOptions?logLevel=logLevel&roleArn=roleArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the logging options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1165613-f5f9-457a-a127-349696561bcf"
            }
          ]
        }
      ]
    },
    {
      "name": "Policy Principals",
      "item": [
        {
          "id": "d300ef3d-feed-4609-bdba-7bd1782fb96b",
          "name": "listPolicyPrincipals",
          "request": {
            "url": "http://example.com/api/?Action=ListPolicyPrincipals?ascendingOrder=ascendingOrder&marker=marker&pageSize=pageSize&policyName=policyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the principals associated with the specified policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d453e91-31ac-4871-81e8-6351f520bb87"
            }
          ]
        }
      ]
    },
    {
      "name": "Policy Versions",
      "item": [
        {
          "id": "ca42175d-44c5-4648-a2da-03380ba94d44",
          "name": "listPolicyVersions",
          "request": {
            "url": "http://example.com/api/?Action=ListPolicyVersions?policyName=policyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the versions of the specified policy and identifies the default version."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87ac1a83-5c4d-44ab-a0ac-08734e33634b"
            }
          ]
        }
      ]
    },
    {
      "name": "Principal Things",
      "item": [
        {
          "id": "a8729d4a-c304-4e89-9f1a-aa523ea1fae4",
          "name": "listPrincipalThings",
          "request": {
            "url": "http://example.com/api/?Action=ListPrincipalThings?maxResults=maxResults&nextToken=nextToken&principal=principal",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the things associated with the specified principal."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95977471-3cec-4406-9728-b9d2a52a9b4b"
            }
          ]
        }
      ]
    }
  ]
}