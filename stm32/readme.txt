La communication est faite avec les lib standard du stm32.
Pas avec HAL ! Libre à vous d'implémenter une autre version.

La seule fonction à appeler est InitializeSPI2()
Les datas sont récupérées dans SPIReceivedValue
Les datas envoyées sont dans SPITransmittedValue

TODO : Un handler d'intéruption peut être ajouté pour agir après transmition.
