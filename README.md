Rearrange
========================

This module is used for rearranging names.
{Lastname, Firstname} -> {Firstname Lastname}

## Example

 * Calling `rearrange_names("Wu, Bill")` will return `"Bill Wu"`
 * Calling `rearrange_names("Wu, Bill D")` will return `"Bill D. Wu"`
 * Calling `rearrange_names("Bill")` will return `"Bill"`
