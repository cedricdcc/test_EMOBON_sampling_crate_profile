---
title: "EMOBON Sampling RO-Crate profile 1.0"
date: 2023-03-15T11:53:24+01:00
draft: false
---
# Sampling RO-Crate profile EMOBON 1.0

## About

* Authors
    * [Cedric Decruw](https://orcid.org/0000-0001-6387-5988)
    * 
* Title: EMOBON Sampling RO-Crate profile 1.0
* Publisher: [vliz-be-opsci](https://open-science.vliz.be/)
* Permalink: https://doi.org/10.18160/ro-crate-1.0
* Version: 1.0
* [Profile Crate ```ro-crate-metadata.json```](./ro-crate-metadata.json)
    * [profile Crate preview](./ro-crate-preview.html)
* [Example RO-Crate ```ro-crate-metadata.json```](./example/ro-crate-metadata.json)
    * [example RO-Crate profile preview](./example/ro-crate-preview.html)

Please use the [issue tracker]() to report any issues or to suggest improvements. (TODO: add link to issue tracker)

## Concepts
This section uses terminology from the [RO-Crate 1.1 specification](https://researchobject.github.io/ro-crate/1.1/).

### Context
The Crate JSON-LD MUST be valid according to the [RO-Crate 1.1](https://researchobject.github.io/ro-crate/1.1/)
```@context``` https://w3id.org/ro/crate/1.1/context

### Crate

The Crate MUST specify a ```license```. The license is assumed to apply to any content of the crate, unless overriden by ```license``` on individual ```File``` entities.

The Crate SHOULD contain a File ```README.md``` at the root level. If present, it SHOULD be ```about``` the Crate ```./``` and SHOULD have ```text/markdown``` as its ```encodingFormat```.


{The following examples are things we could specify for our EMOBON sampling RO-Crate profile.}

The Crate COULD contain a Dataset (directory) data entity of type ```["Dataset"]``` with identifier ```test/``` to hold tests.

The Crate COULD contain a Dataset (directory) data entity of type ```["Dataset"]``` with identifier ```examples/``` to hold examples.
