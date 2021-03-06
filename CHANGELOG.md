3.5.4

- Framework upgrade

3.5.1

- Added procedure for listing models
- Added procedure for refreshing a pipeline

3.4.9.52.16

- Passing an empty text throws now an exception before hitting the TextProcessor
- ConceptNet procedure now accepts languages, directions and POS filtering

3.4.9.52.15

- [BC] Changes to the Concept request signature, check README.md for new signature
- [BC] Users should now download the language model from Stanford and add it to the plugins directory

3.4.8.52.14

- Enable EE modules to hook migrations

3.4.6.52.13

- TagOccurrence nodes now receive the NE_$$$ label
- TextRank persistence is now decouple from computation
- Persistence can now store OptimizedCoref from NLP-EE
- Ability to listen to Annotation Events before it is stored
- AnnotatedText object is now serializable and deserializable to json string

3.4.6.52.12

- Added the ability to whitelist only certain words in a pipeline
- Fixed an issue with the PDF Parser not returning the first page
- Added the ability to parse WebVTT file formats
- Added `utils.listFiles` and `utils.walkdir` procedures
- Added the ability to pass a custom UserAgent for TIKA