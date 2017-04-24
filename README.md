# dogstatsd-iscbind

Surface metrics from [ISC BIND DNS servers](https://www.isc.org/downloads/bind/)
agents and proxies into [datadog](https://www.datadoghq.com/) via
[dogstatsd](http://docs.datadoghq.com/guides/dogstatsd/).

## Requirements

* Perl
* Perl module [DataDog::DogStatsd](https://github.com/binary-com/dogstatsd-perl) 
  -- also included in the [lib](lib) directory for convenience
* Perl module [File::Slurp](https://metacpan.org/pod/File::Slurp)

## Metrics generated

| metric				| description 						|
| ----					| ----							|


## Support

Please file tickets via [github](https://github.com/fini-net/dogstatsd-iscbind/issues).
MR's welcomed whether I [plan to do it](TODO.md) or not.
