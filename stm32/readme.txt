La communication est faite avec les lib standard du stm32.
Pas avec HAL ! Libre � vous d'impl�menter une autre version.

La seule fonction � appeler est InitializeSPI2()
Les datas sont r�cup�r�es dans SPIReceivedValue
Les datas envoy�es sont dans SPITransmittedValue

TODO : Un handler d'int�ruption peut �tre ajout� pour agir apr�s transmition.
