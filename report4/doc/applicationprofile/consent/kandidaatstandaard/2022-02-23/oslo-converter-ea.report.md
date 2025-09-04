#||# oslo-converter-ea for diagram OSLO-Consent

#||# -------------------------------------

2025-09-04T07:59:07.890Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Consent:DPV:LegalBasis:(LegalBasis -> PersonalDataHandling))

2025-09-04T07:59:07.891Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Consent:GConsent:DataController:(DataController -> Consent))

2025-09-04T07:59:07.891Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Consent:GConsent:DataController:(DataController -> PersonalData))

2025-09-04T07:59:07.891Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Consent:GConsent:DataController:(DataController -> DataProcessor))

2025-09-04T07:59:07.894Z info: Connector Model:OSLO-Consent:GConsent:MinorDataSubject:(MinorDataSubject -> DataSubject) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.895Z info: Connector Model:OSLO-Consent:GConsent:Consent:(Consent -> Delegation) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.895Z info: Connector Model:OSLO-Consent:GConsent:Consent:(Consent -> LegalBasis) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.895Z info: Connector Model:OSLO-Consent:GConsent:Delegation:(Delegation -> DataSubject) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.895Z info: Connector Model:OSLO-Consent:CCCEV:Criterion:(Criterion -> informationRequired) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.896Z info: Connector Model:OSLO-Consent:GConsent:GivenConsent:(GivenConsent -> Consent) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.896Z info: Connector Model:OSLO-Consent:CCCEV:informationRequired:(informationRequired -> EvidenceType) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.896Z info: Connector Model:OSLO-Consent:GConsent:DataSubject:(DataSubject -> Consent) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.896Z info: Connector Model:OSLO-Consent:GConsent:DataController:(DataController -> Consent) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.896Z info: Connector Model:OSLO-Consent:DPV:PersonalDataHandling:(PersonalDataHandling -> DataSubject) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.897Z info: Connector Model:OSLO-Consent:DPV:PersonalDataHandling:(PersonalDataHandling -> Purpose) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.897Z info: Connector Model:OSLO-Consent:DPV:PersonalDataHandling:(PersonalDataHandling -> Processing) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.897Z info: Connector Model:OSLO-Consent:DPV:DataProcessor:(DataProcessor -> ThirdParty) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.897Z info: Connector Model:OSLO-Consent:OSLO-Consent:Expiry:(Expiry -> Criterion) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.897Z info: Connector Model:OSLO-Consent:GConsent:PersonalData:(PersonalData -> Filter) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.897Z info: Connector Model:OSLO-Consent:OSLO-Organisation:RegisteredOrganisation:(RegisteredOrganisation -> Agent) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.897Z info: Connector Model:OSLO-Consent:OSLO-Person:RegisteredPerson:(RegisteredPerson -> Agent) is not an association with a source role. Ignoring this connector.

2025-09-04T07:59:07.898Z info: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model). Using fallback URI (http://todo.com/) instead.

2025-09-04T07:59:07.899Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:ObjectDiagrams). Using fallback URI (http://todo.com/) instead.

2025-09-04T07:59:07.899Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:GConsent). Using fallback URI (http://todo.com/) instead.

2025-09-04T07:59:07.899Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:DPV). Using fallback URI (http://todo.com/) instead.

2025-09-04T07:59:07.899Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:CCCEV). Using fallback URI (http://todo.com/) instead.

2025-09-04T07:59:07.899Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:OSLO-Generic). Using fallback URI (http://todo.com/) instead.

2025-09-04T07:59:07.899Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:OSLO-Person). Using fallback URI (http://todo.com/) instead.

2025-09-04T07:59:07.899Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:OSLO-Organisation). Using fallback URI (http://todo.com/) instead.

2025-09-04T07:59:07.899Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:Hulppakket). Using fallback URI (http://todo.com/) instead.

2025-09-04T07:59:07.902Z warn: [ConnectorConverterHandler]: Connector (providedConsent) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-04T07:59:07.902Z warn: [ConnectorConverterHandler]: Connector (hasDataSubject) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-04T07:59:07.902Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (hasDataSubject) and the fallback URI (http://todo.com/) will be assigned.

2025-09-04T07:59:07.902Z warn: [ConnectorConverterHandler]: Connector (OSLO::isGivenFor) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-04T07:59:07.902Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (OSLO::isGivenFor) and the fallback URI (http://todo.com/) will be assigned.

2025-09-04T07:59:07.903Z warn: [ConnectorConverterHandler]: Connector (hasPurpose) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-04T07:59:07.903Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (hasPurpose) and the fallback URI (http://todo.com/) will be assigned.

2025-09-04T07:59:07.903Z warn: [ConnectorConverterHandler]: Connector (hasProcessing) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-04T07:59:07.903Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (hasProcessing) and the fallback URI (http://todo.com/) will be assigned.

2025-09-04T07:59:07.903Z warn: [ConnectorConverterHandler]: Connector (hasRetentionPeriod) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-04T07:59:07.903Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (hasRetentionPeriod) and the fallback URI (http://todo.com/) will be assigned.

2025-09-04T07:59:07.903Z warn: [ConnectorConverterHandler]: Connector (isContingentOn) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-04T07:59:07.903Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (isContingentOn) and the fallback URI (http://todo.com/) will be assigned.

2025-09-04T07:59:07.903Z warn: [ConnectorConverterHandler]: Connector (hasFilter) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-04T07:59:07.903Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (hasFilter) and the fallback URI (http://todo.com/) will be assigned.

2025-09-04T07:59:07.912Z warn: [ConverterHandler]: Entity with path Model:OSLO-Consent:OSLO-Person:RegisteredPerson has already a value for label-en in language en, but will be overwritten.

2025-09-04T07:59:07.912Z warn: [ConverterHandler]: Entity with path Model:OSLO-Consent:OSLO-Person:RegisteredPerson has already a value for label-en in language en, but will be overwritten.

2025-09-04T07:59:07.913Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:OSLO-Consent:GConsent:Consent:location).

2025-09-04T07:59:07.916Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:OSLO-Consent:OSLO-Generic:Identifier:attributedBy).

#||# -------------------------------------

