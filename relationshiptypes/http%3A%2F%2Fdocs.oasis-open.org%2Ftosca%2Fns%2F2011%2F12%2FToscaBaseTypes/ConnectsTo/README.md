# ConnectsTo [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

> Establishes a connection between two nodes

The properties for the IA are searched in the stack.
Assume that A ConnectsTo B.
Then A is the source and B is the target.

The implementation of the `connectTo` method may be implemented at A or B.
The name of the operation properties are matched to property names in the stacks of A and B.
It depends on the placement of the IA where the properties are searched.
The are always searched at the opposite end.
So, in case the IA is attached to A, the properties are searched at B.
In case properties should be explicitly searched for at the source or target, they have to prefixed with `source_`/`target_` at the operation definition.

## Properties

- `ChannelType`

## Haftungsausschluss

Dies ist ein Forschungsprototyp und enthält insbesondere Beiträge von Studenten.
Diese Software enthält möglicherweise Fehler und funktioniert möglicherweise, insbesondere bei variierten oder neuen Anwendungsfällen, nicht richtig.
Insbesondere beim Produktiveinsatz muss 1. die Funktionsfähigkeit geprüft und 2. die Einhaltung sämtlicher Lizenzen geprüft werden.
Die Haftung für entgangenen Gewinn, Produktionsausfall, Betriebsunterbrechung, entgangene Nutzungen, Verlust von Daten und Informationen, Finanzierungsaufwendungen sowie sonstige Vermögens- und Folgeschäden ist, außer in Fällen von grober Fahrlässigkeit, Vorsatz und Personenschäden ausgeschlossen.

## Disclaimer of Warranty

Unless required by applicable law or agreed to in writing, Licensor provides the Work (and each Contributor
provides its Contributions) on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express
or implied, including, without limitation, any warranties or conditions of TITLE, NON-INFRINGEMENT,
MERCHANTABILITY, or FITNESS FOR A PARTICULAR PURPOSE. You are solely responsible for determining the
appropriateness of using or redistributing the Work and assume any risks associated with Your exercise of
permissions under this License.
