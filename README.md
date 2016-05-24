#JAX-RS Nameformatter

#Description
Creates metrics for RESTFUL webservices on the server.  Creates a metric for each service that allows you to see the response time and number of hits, and also if any responses take longer than 30 seconds.

## Short Description

Creates metrics for JAX-RS Services

##APM version

9.x and higher.

##Supported third party versions

This fieldpack is agnostic to 3rd party frameworks.  As long as the framework uses JAX-RS annotations, then it should work.

##Third party versions tested with.

Tested and working with Jersey, but should work with others.

##Limitations

Doesn't work with JAX-RS client calls.  Could be extended to do this.  Create an issue if you want that feature.

##License

http://www.apache.org/licenses/LICENSE-2.0.html

Please review the LICENSE file in this repository. Licenses may vary by repository. Your download and use of this software constitutes your agreement to this license.

##Installation Instructions

copy ca.apm.fieldpacks.agent.jaxrs.jar to <ca apm agent>/core/ext
copy JAXRSNameFormatter.pbd to <ca apm agent>/core/config
restart the agent

##Configuration

No configuration required

##Usage Instructions

Metrics will be created under JAX-RS folder.

##Metric description

Creates a metric for each service that allows you to see the response time and number of hits, and also if any responses take longer than 30 seconds.

##Name Formatter Replacements

{path} is replaced with the service name

##Debugging and Troubleshooting

How to debug and troubleshoot the field pack.

##Support

This document and associated tools are made available from CA Technologies as examples and provided at no charge as a courtesy to the CA APM Community at large. This resource may require modification for use in your environment. However, please note that this resource is not supported by CA Technologies, and inclusion in this site should not be construed to be an endorsement or recommendation by CA Technologies. These utilities are not covered by the CA Technologies software license agreement and there is no explicit or implied warranty from CA Technologies. They can be used and distributed freely amongst the CA APM Community, but not sold. As such, they are unsupported software, provided as is without warranty of any kind, express or implied, including but not limited to warranties of merchantability and fitness for a particular purpose. CA Technologies does not warrant that this resource will meet your requirements or that the operation of the resource will be uninterrupted or error free or that any defects will be corrected. The use of this resource implies that you understand and agree to the terms listed herein.

Although these utilities are unsupported, please let us know if you have any problems or questions by adding a comment to the CA APM Community Site area where the resource is located, so that the Author(s) may attempt to address the issue or question.

Unless explicitly stated otherwise this field pack is only supported on the same platforms as the APM core agent. See APM Compatibility Guide.

### Support URL

https://github.com/CA-APM/fieldpack.jaxrs/issues

##Contributing

The CA APM Community is the primary means of interfacing with other users and with the CA APM product team. The developer subcommunity is where you can learn more about building APM-based assets, find code examples, and ask questions of other developers and the CA APM product team.

If you wish to contribute to this or any other project, please refer to easy instructions available on the CA APM Developer Community.

## Categories

Webservices
