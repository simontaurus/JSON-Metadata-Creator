# JSON-Metadata-Creator
Creates json files with schemas and web forms

Webtool for the form-based creation of json metadata files,
using nested json schemas and https://github.com/json-editor/json-editor

Schemas could be created and extended with https://json.bootsphp.com/jsonSchemaCreator/

## Background

Metadata is any information that is needed to understand data in its context.
Typically, this is information that is discussed on the phone or by e-mail with a person to whom data is sent.
However, the "classic" way of transmission is completely unstructured and usually only bilateral.
Therefore, a lot of metadata is lost and often only the hard-to-interpret actual data remains.
With this tool it should be possible to create at least basic structured and easily shareable metadata.

## Implementation

JSON Metadata Creator is an interactive web form, accessible at https://simontaurus.github.io/JSON-Metadata-Creator/
The structure of the form is based on modular schemas that define the form and structure of the data.
The basic schema can be extended with any number of complementary schemas.
The input can then be saved directly as a JSON file & uploaded to a cloud folder.
Alternatively, a link can be generated with which the completed form can be accessed directly.



