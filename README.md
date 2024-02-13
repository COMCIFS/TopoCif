# Topology Dictionary

Definitions of CIF data names for topology description.

## Warning

[This dictionary](Topology.dic) is the latest **draft** version. Definitions are subject to change and software should be careful not to hard-code information.
The latest approved topology dictionary is available from the [IUCr CIF website](https://www.iucr.org/resources/cif/dictionaries).

## Contributing

Contributions are very welcome, both from powder diffraction experts and people with technical CIF knowledge.
Ways of contributing include:

1. Raising an issue, including suggesting a new data name (see "Issues" tab above).
2. Creating a pull request with suggested improvements to the dictionary.
3. Commenting on already existing issues.
4. Reviewing pull requests.

If the "Github way" is not familiar to you, we suggest looking at [some closed issues](https://github.com/COMCIFS/TopoCif/issues?q=is%3Aissue+is%3Aclosed) and [some closed pull requests](https://github.com/COMCIFS/TopoCif/issues?q=is%3Apr+is%3Aclosed) to see how the process works.
You may also find [this wiki entry](https://github.com/COMCIFS/cif_core/wiki/Getting-started-with-Github-and-Git-for-development-of-CIF-dictionaries) helpful.

## Update guidelines

In general, any changes to the semantic content of the dictionary should be presented as a pull request.
Someone other than the author of the original pull request should merge the pull request once they are satisfied that the pull request is suitable for inclusion.
This protocol is not necessary for changes to the layout of the dictionary that do not change the meaning of any data names.

## Repository layout

Top-level files [TopoCif_chapter.docx](TopoCif_chapter.docx) and [Topology.dic](Topology.dic) are the latest draft versions of the chapter and the dictionary respectively.

Directory content:
* `chapter/`    old versions of the Word document chapter.
* `dictionary/` old versions of the CIF dictionary.
* `examples/`   seven examples appearing in the dictionary (since version `0.9.6`).
