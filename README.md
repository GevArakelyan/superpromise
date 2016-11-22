# superpromise

**PURPOSE:** Provide a super project for promise related groups

**AUTHOR:** David Sankel (dsankel)

## Description

The `superpromise` superproject contains groups related to promises. The intent
is to provide a convenient way to develop promises and groups frequently
modified in tandem with them.

## TODO

- Add component-level documentation and tests for dplp's components
  and update dplp's documentation.
  - dplp_promise
  - dplp_resolver (perhaps we want a dplp_resolverachtype to help unit test
    dplp_promise)
- Rename 'dplp::Promise' to 'dplp::promise'.
- Add documentation of system error exceptions to apltcp_channel.
- Add documentation for "ArchType".
- Add documentation for dplm17_variant.
- Fix the included guards. INCLUDED should be coming first.
- Consider a generalization of `dplmrts::AnyTuple` which is satisified when an
  arbitrary template class is matched.
- Add to (new?) standard.
  - "This concept is satisfied by"
  - Markdown formatting for README's, etc.
- Figure out if we need a "Package Synopsis" *and* a "Package Overview" when
  documenting package groups.
- Make cmsfm_findasio more robust when it cannot find the 'asio' directory.
