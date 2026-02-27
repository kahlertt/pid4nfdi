<!--
author: Rorie Edmunds (adapted for LiaScript)
email: 
version: 0.1
language: en
narrator: US English Female
comment: A short training module on IGSN IDs for repository managers.
license: CC BY 4.0
-->

# Registering IGSN IDs: A Guide for Repository Managers

This module gives you a practical overview of **International Generic Sample
Numbers (IGSN IDs)** — what they are, what they can be assigned to, and how
your organization can start registering them.

**Estimated time:** ~15 minutes

---

## What is the IGSN ID?

The **IGSN ID** is a globally unique and persistent identifier (PID) for
**material samples** — that is, physical objects.

Its core purpose is to enable transparent and traceable connections among
research activities and objects, including samples, collections, instruments,
grants, data, publications, people, and organizations.

> **Key point for repository managers:** IGSN IDs are functionally
> **DataCite DOIs**. This is the result of a 2021 partnership between
> IGSN e.V. and DataCite. If your repository already registers DataCite
> DOIs, you are already most of the way there.

This means IGSN IDs benefit from:

- The robust, internationally recognized DOI infrastructure
- DataCite's long-term sustainability guarantees
- Existing DataCite tooling (Fabrica, APIs, Commons)

---

## What can receive an IGSN ID?

An IGSN ID can be assigned to **any material sample from any discipline** —
including living specimens and lab-synthesized materials.

Note that the IGSN ID is assigned to the **physical object itself**, not to
images of it or analytical data about it.

Beyond individual samples, IGSN IDs can also be assigned to:

**Sample aggregations**
A collection of related objects that need to be referenced as a whole.
Individual samples within the collection become *children* of the parent
and can be linked in the metadata.

**Sample collection sites**
The physical location where field sampling took place. Samples collected
there are children of the site.

**Ephemeral samples**
Samples that no longer exist (e.g., consumed during analysis) can still
receive an IGSN ID, provided the metadata clearly states the sample's
current status.

---

## Quick Check ✅

Here are two short questions to confirm the key points.

**Question 1**

Which of the following statements about IGSN IDs is correct?

    [( )] IGSN IDs are a completely separate system from DOIs and require a new registration infrastructure.
    [(X)] IGSN IDs are functionally DataCite DOIs and use the same underlying infrastructure.
    [( )] IGSN IDs can only be assigned to geoscience samples.
    [( )] IGSN IDs replace local sample identifiers and require renaming all existing samples.

**Question 2**

Your repository holds a collection of soil cores. A researcher has already
consumed several cores during lab analysis. Can those destroyed samples
still receive an IGSN ID?

    [(X)] Yes — ephemeral samples can be registered, as long as the metadata documents their current status.
    [( )] No — only samples that still physically exist can be registered.
    [( )] Only if the researcher provides photographic evidence of the sample prior to destruction.