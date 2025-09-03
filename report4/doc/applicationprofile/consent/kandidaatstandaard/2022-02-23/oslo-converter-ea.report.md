#||# oslo-converter-ea for diagram OSLO-Consent

#||# -------------------------------------

2025-09-03T14:52:36.082Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Consent:DPV:LegalBasis:(LegalBasis -> PersonalDataHandling))

2025-09-03T14:52:36.084Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Consent:GConsent:DataController:(DataController -> Consent))

2025-09-03T14:52:36.084Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Consent:GConsent:DataController:(DataController -> PersonalData))

2025-09-03T14:52:36.084Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Consent:GConsent:DataController:(DataController -> DataProcessor))

2025-09-03T14:52:36.087Z info: Connector Model:OSLO-Consent:GConsent:MinorDataSubject:(MinorDataSubject -> DataSubject) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.087Z info: Connector Model:OSLO-Consent:GConsent:Consent:(Consent -> Delegation) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.087Z info: Connector Model:OSLO-Consent:GConsent:Consent:(Consent -> LegalBasis) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.087Z info: Connector Model:OSLO-Consent:GConsent:Delegation:(Delegation -> DataSubject) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.088Z info: Connector Model:OSLO-Consent:CCCEV:Criterion:(Criterion -> informationRequired) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.088Z info: Connector Model:OSLO-Consent:GConsent:GivenConsent:(GivenConsent -> Consent) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.088Z info: Connector Model:OSLO-Consent:CCCEV:informationRequired:(informationRequired -> EvidenceType) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.088Z info: Connector Model:OSLO-Consent:GConsent:DataSubject:(DataSubject -> Consent) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.088Z info: Connector Model:OSLO-Consent:GConsent:DataController:(DataController -> Consent) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.089Z info: Connector Model:OSLO-Consent:DPV:PersonalDataHandling:(PersonalDataHandling -> DataSubject) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.089Z info: Connector Model:OSLO-Consent:DPV:PersonalDataHandling:(PersonalDataHandling -> Purpose) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.089Z info: Connector Model:OSLO-Consent:DPV:PersonalDataHandling:(PersonalDataHandling -> Processing) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.089Z info: Connector Model:OSLO-Consent:DPV:DataProcessor:(DataProcessor -> ThirdParty) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.089Z info: Connector Model:OSLO-Consent:OSLO-Consent:Expiry:(Expiry -> Criterion) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.089Z info: Connector Model:OSLO-Consent:GConsent:PersonalData:(PersonalData -> Filter) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.089Z info: Connector Model:OSLO-Consent:OSLO-Organisation:RegisteredOrganisation:(RegisteredOrganisation -> Agent) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.089Z info: Connector Model:OSLO-Consent:OSLO-Person:RegisteredPerson:(RegisteredPerson -> Agent) is not an association with a source role. Ignoring this connector.

2025-09-03T14:52:36.090Z info: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model). Using fallback URI (http://todo.com/) instead.

2025-09-03T14:52:36.091Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:ObjectDiagrams). Using fallback URI (http://todo.com/) instead.

2025-09-03T14:52:36.091Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:GConsent). Using fallback URI (http://todo.com/) instead.

2025-09-03T14:52:36.091Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:DPV). Using fallback URI (http://todo.com/) instead.

2025-09-03T14:52:36.091Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:CCCEV). Using fallback URI (http://todo.com/) instead.

2025-09-03T14:52:36.091Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:OSLO-Generic). Using fallback URI (http://todo.com/) instead.

2025-09-03T14:52:36.091Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:OSLO-Person). Using fallback URI (http://todo.com/) instead.

2025-09-03T14:52:36.091Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:OSLO-Organisation). Using fallback URI (http://todo.com/) instead.

2025-09-03T14:52:36.091Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Consent:Hulppakket). Using fallback URI (http://todo.com/) instead.

2025-09-03T14:52:36.094Z warn: [ConnectorConverterHandler]: Connector (providedConsent) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-03T14:52:36.094Z warn: [ConnectorConverterHandler]: Connector (hasDataSubject) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-03T14:52:36.094Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (hasDataSubject) and the fallback URI (http://todo.com/) will be assigned.

2025-09-03T14:52:36.094Z warn: [ConnectorConverterHandler]: Connector (OSLO::isGivenFor) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-03T14:52:36.094Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (OSLO::isGivenFor) and the fallback URI (http://todo.com/) will be assigned.

2025-09-03T14:52:36.094Z warn: [ConnectorConverterHandler]: Connector (hasPurpose) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-03T14:52:36.094Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (hasPurpose) and the fallback URI (http://todo.com/) will be assigned.

2025-09-03T14:52:36.094Z warn: [ConnectorConverterHandler]: Connector (hasProcessing) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-03T14:52:36.094Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (hasProcessing) and the fallback URI (http://todo.com/) will be assigned.

2025-09-03T14:52:36.094Z warn: [ConnectorConverterHandler]: Connector (hasRetentionPeriod) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-03T14:52:36.094Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (hasRetentionPeriod) and the fallback URI (http://todo.com/) will be assigned.

2025-09-03T14:52:36.095Z warn: [ConnectorConverterHandler]: Connector (isContingentOn) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-03T14:52:36.095Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (isContingentOn) and the fallback URI (http://todo.com/) will be assigned.

2025-09-03T14:52:36.095Z warn: [ConnectorConverterHandler]: Connector (hasFilter) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-09-03T14:52:36.095Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (hasFilter) and the fallback URI (http://todo.com/) will be assigned.

2025-09-03T14:52:36.102Z warn: [ConverterHandler]: Entity with path Model:OSLO-Consent:OSLO-Person:RegisteredPerson has already a value for label-en in language en, but will be overwritten.

2025-09-03T14:52:36.103Z warn: [ConverterHandler]: Entity with path Model:OSLO-Consent:OSLO-Person:RegisteredPerson has already a value for label-en in language en, but will be overwritten.

2025-09-03T14:52:36.104Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:OSLO-Consent:GConsent:Consent:location).

2025-09-03T14:52:36.107Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:OSLO-Consent:OSLO-Generic:Identifier:attributedBy).

#||# -------------------------------------

