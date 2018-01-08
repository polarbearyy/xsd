# xsd

Each xsd must have the root element:
<xs:schema>
</xs:schema>

The root element can have these attributes:

xmlns:xs="http://www.w3.org/2001/XMLSchema"
It creates an alias for the namespace "http://www.w3.org/2001/XMLSchema"
xs:simpleType refers to simpleType in this name space.

xmlns="https://www.w3schools.com"
xmlns indicates default namespace of this document.

targetNamespace="https://www.w3schools.com"
It defines the target namespace.

xmlns:tns="https://www.w3schools.com" created an alias for the the target namespace.

elementFormDefault="qualified"
It indicates any element used in the document must be namespace qualified.
