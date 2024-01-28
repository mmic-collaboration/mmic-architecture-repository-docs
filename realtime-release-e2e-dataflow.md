# End-to-end Data Flow of Sensor Events for the Real-time Release use-case

Here we show the end to end flow of sensor events from the source sensor on the manufacturing equipment 

  ![archi collab config](images/realtime-release-e2e-dataflow.md "End-to-end sensor data flow")

  <br>
  <br>
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
  <br>

| Stage->   | Sensor | Sensor Broker | Process Broker (Edge) | Data-lake Curated (Cloud) | Data-lake Harmonisec (Cloud) |
| --------  | ------ | -------- | ------- | ------- |
| Domain    | (raw)  | PLANT  | PROCESS    |PROCESS   |(harmonised)|
| CDM       | NA     | [PLANT CDM](https://github.com/mmic-collaboration/plant-domain-model)|[PROCESS CDM](https://github.com/mmic-collaboration/process-domain-model)|[PROCESS CDM](https://github.com/mmic-collaboration/process-domain-model)|(harmonised TBD)|
| LDM       | TBD    |[PLANT LDM](https://github.com/mmic-collaboration/plant-domain-model/blob/development/model/Graphics/PLANT-Domain-LDM.png)|[PROCESS LDM](https://github.com/mmic-collaboration/process-domain-model/blob/development/model/Graphics/PROCESS-Domain-LDM.png)|[PROCESS LDM](https://github.com/mmic-collaboration/process-domain-model/blob/development/model/Graphics/PROCESS-Domain-LDM.png)|(harmonised LDM TBD)|
| PDM       | TBD    | [How to setup PAT Authentication for Git](how-to-setup-pat-authentication-for-git.md)  | PROCESS    |PROCESS   |(harmonised)|
| Sample    | TBD    | TBD  | TBD    | TBD   |TBD|


## Code
 - HTTPS: https://github.com/mmic-collaboration/mmic-architecture-repository.git
 - SSH: git@github.com:mmic-collaboration/mmic-architecture-repository.git
