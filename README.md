# Validationpackage MIO Telemedical (Telemedizinisches) Monitoring Version 1.0.0

Disclaimer:
This service is intended to help with the validation process. However, please note there is no claim to completeness, correctness or reliability. 

Introduction:
This archive is supposed to be a guidance for developers in the implementation process of the medicinal information objects (MIOs). It contains the "Basis-Profile" (FHIR-profiles defined for reuse in various cases, e.g. "Patient" for the person who is being treated), the FHIR-resources used for the specific MIO, the validator and practical examples. Altogether, this package serves as an exemplary validation environment. The necessary dependencies are provided and can be integrated directly. 

Alternatively, the dependencies can also be found here:
- de.basisprofil.r4 0.9.13: https://simplifier.net/packages/de.basisprofil.r4/0.9.13
- kbv.basis 1.2.1: https://simplifier.net/packages/kbv.basis/1.2.1
- kbv.mio.tele 1.0.0: https://simplifier.net/packages/kbv.mio.tele/1.0.0

The version of the validator, which was used by the mio42 GmbH, is included. If the version provided should cause any problems, you may also use the most recent one. All releases can be found here:
- https://github.com/hapifhir/org.hl7.fhir.core/releases

For a thorough documentation on the use of the validator, please follow this link:
- https://confluence.hl7.org/display/FHIR/Using+the+FHIR+Validator

You can use the following command to validate the examples:

REAL_EXAMPLE_1_KBV_PR_MIO_TELE_Bundle:
```
java -jar validator_cli.jar .\Example\REAL_EXAMPLE_1_KBV_PR_MIO_TELE_Bundle.xml -ig "hl7.fhir.core#4.0.1" -ig .\KBV-Base -ig .\HL7-Base-de -ig .\FHIR-Specification -recurse
```

REAL_EXAMPLE_2_KBV_PR_MIO_TELE_Bundle:
```
java -jar validator_cli.jar .\Example\REAL_EXAMPLE_2_KBV_PR_MIO_TELE_Bundle.xml -ig "hl7.fhir.core#4.0.1" -ig .\KBV-Base -ig .\HL7-Base-de -ig .\FHIR-Specification -recurse
```

REAL_EXAMPLE_3_KBV_PR_MIO_TELE_Bundle:
```
java -jar validator_cli.jar .\Example\REAL_EXAMPLE_3_KBV_PR_MIO_TELE_Bundle.xml -ig "hl7.fhir.core#4.0.1" -ig .\KBV-Base -ig .\HL7-Base-de -ig .\FHIR-Specification -recurse
```

Please note that a current version of Java is required (we would recommend the most recent one).


# Validierungspaket MIO Telemedizinisches Monitoring Version 1.0.0

Disclaimer: 
Der Service zur Validierung erhebt keinen Anspruch auf Vollständigkeit, Korrektheit sowie Verbindlichkeit.

Einführung:
Dieses Archiv soll als Orientierungshilfe für Entwickler:innen bei der Umsetzung der MIOs dienen. 
Es enthält die verwendeten Basis-Profile, die Ressourcen des MIO, den Validator und Praxisbeispiele. Damit stellt diese Sammlung eine beispielhafte Validierungsumgebung dar. Die notwendigen Abhängigkeiten sind bereitgestellt und koennen direkt eingebunden werden.


Die Dependencies finden Sie alternativ unter folgenden links:

- de.basisprofil.r4 0.9.13: https://simplifier.net/packages/de.basisprofil.r4/0.9.13
- kbv.basis 1.2.1: https://simplifier.net/packages/kbv.basis/1.2.1
- kbv.mio.tele 1.0.0: https://simplifier.net/packages/kbv.mio.tele/1.0.0

Die Version des Validators, welche von der mio42 GmbH für die Validierung verwendet wurde, ist enthalten. Sollte diese zu Prolemen führen, können Sie auch die aktuelle  Version des Validators nutzen. Alle Releases finden Sie unter: 
- https://github.com/hapifhir/org.hl7.fhir.core/releases

Eine Ausführliche Dokumentation zur Verwendung des Validators finden Sie hier:
- https://confluence.hl7.org/display/FHIR/Using+the+FHIR+Validator

Zur Validierung der Beispiele können Sie folgenden Aufruf verwenden:

REAL_EXAMPLE_1_KBV_PR_MIO_TELE_Bundle:
```
java -jar validator_cli.jar .\Example\REAL_EXAMPLE_1_KBV_PR_MIO_TELE_Bundle.xml -ig "hl7.fhir.core#4.0.1" -ig .\KBV-Base -ig .\HL7-Base-de -ig .\FHIR-Specification -recurse
```

REAL_EXAMPLE_2_KBV_PR_MIO_TELE_Bundle:
```
java -jar validator_cli.jar .\Example\REAL_EXAMPLE_2_KBV_PR_MIO_TELE_Bundle.xml -ig "hl7.fhir.core#4.0.1" -ig .\KBV-Base -ig .\HL7-Base-de -ig .\FHIR-Specification -recurse
```

REAL_EXAMPLE_3_KBV_PR_MIO_TELE_Bundle:
```
java -jar validator_cli.jar .\Example\REAL_EXAMPLE_3_KBV_PR_MIO_TELE_Bundle.xml -ig "hl7.fhir.core#4.0.1" -ig .\KBV-Base -ig .\HL7-Base-de -ig .\FHIR-Specification -recurse
```

Weitere Voraussetzung ist eine aktuelle Java Version.
