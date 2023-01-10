Delete this link at the end of the specification process:  
- [Roadmap to Specification](../../issues/1)

# Linkid2LtpTranslator

### Location
The Linkid2LtpTranslator is part of the HighPerformanceNetworkInterface.

### Description
The Linkid2LtpTranslator is supporting e.g. the Resolver and the FineGrainedLinkDataCollector in creating a valid RESTCONF URI. It is translating the Telefonica Link ID from within x:akta or APT into the UUID of an AirInterface LTP. Linkid2LtpTranslator is continuously going through the MicroWaveDeviceInventory and updating its internal translation table. Concrete translation results are provided on individual service requests.

### Relevance
The Linkid2LtpTranslator serves as a "phone book". 
Other applications require it for addressing live network resources.

### Resources
- [Specification](./spec/)
- [TestSuite](./testing/)
- [Implementation](./server/)

### Comments
This application will be specified during training for ApplicationOwner.
