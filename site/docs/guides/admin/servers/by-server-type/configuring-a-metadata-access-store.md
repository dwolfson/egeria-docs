<!-- SPDX-License-Identifier: CC-BY-4.0 -->
<!-- Copyright Contributors to the Egeria project 2020. -->

# Configuring a Metadata Access Store

A *[Metadata Access Store](/concepts/metadata-access-store)* provides a metadata repository with REST APIs for working with metadata.  It may send notifications when metadata changes and be a [member of one or more cohorts](/concepts/cohort-member).

is configured by creating a [configuration document](/concepts/configuration-document). Below are the outline structures of the server's configuration document.


![Configuration document for a metadata access store](/concepts/metadata-access-store.svg)

--8<-- "snippets/admin/configuring-standard-sections.md"

??? info "Configuring the local repository store"
    --8<-- "snippets/admin/configuring-the-local-repository.md"

??? info "Registering the server with a cohort"
    --8<-- "snippets/admin/configuring-registration-to-a-cohort.md"

??? info "Configuring the access services"
    --8<-- "snippets/admin/configuring-the-access-services.md"

??? info "(Optional) Configuring the open metadata archives to load on server start up"
    --8<-- "snippets/admin/configuring-the-startup-archives.md"

--8<-- "snippets/abbr.md"
