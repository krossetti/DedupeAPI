# DedupeAPI
This is a git repo for conducting a data pull from an API while conducting a deduplication of its entities to a DB

Build a potential API client that utilized USPS address checker. This will build on a gazatter index that normalized addresses. What we would be performing is geocoding the addresses utilizing googlemaps API
that would translate the address into LAT/LONG data which we would then compare using the haverstein distance metric

Gazzatter gives fuzzy look-ups; think of when you enter in an address into your map app or uber, there is an index dictionary of addresses that on on-file or it will assign the location to the closest one on file.

There are two objectives we are trying to accomplish, a primary and secondary:

Primary) Utilize a program to do all three functions pull the data via an API, compute the distance metrics for comparison, and lastly deduplicate the raw and computed pairwise.

Secondary) Utilize multiple programs to accomplish all three functions pull the data via an API and dump into a DB, and a second to compute the distance metrics for comparison and deduplicate both the raw and computed pairwise.
