@staruml
scale 3

abstract class MediosTranspote{

}

class TrabsporteAcuatico{
    -veocidad: int
    -capacidad: String
    +aumentarCapacidad():void 

}
class Barco{
    -puertoOrigen: String
    -puertoDestino: String
    +abordadPasajeros():void
}

MediosTransporte <|-- TransporteAcuatico
TransporteAcuatico <|-- Barco:interfaz

@enduml

