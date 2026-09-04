# ChirpStack Configuration

## Gateway
Region ID: eu868  
Region common-name: EU868  
Gateway ID (EUI64): eui for your gateway  

## Device Profiles
**Name:** Dragino  
**Region:** EU868  
**Region configuration:** EU868  
**MAC version:** LoRaWAN 1.0.3  
**Regional parameter revision:** A  
**ADR algorithm:** Default ADR algorithm (LoRa only)  

#### Payload codec\Codec functions
**Payload codec:** JavaScript functions  
**Codec functions:** [Link to file](codec_function.js)

## Applications
**Name:** Dragino Termometer  

#### Add Device:
**Name:** dragino1 (for example)  
**Device EUI (EUI64):** eui for your thermometer  
**Join EUI (EUI64):** generate  
**Device profile:** Tenant / Dragino

**OTAA keys:**  
**Application key:** for your thermometer, often sent together with device eui.

