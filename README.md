// HERMILO PALOMEQUE GOMEZ
// GRUPO 001  21/02/21
#include <iostream>
using namespace std;

int main()
{
    int opcion, cita, HdT, CdT;
    float T = 0, PreU, PUT;
    char NdP, tratamiento, desc;

    do {
        cout << "-----Elija una opcion segun el numero-----" << endl;
        cout << " 1 Agendar cita " << endl;
        cout << " 2 Modificar cita " << endl;
        cout << " 3 Eliminar cita" << endl;
        cout << " 4 Lista de citas vigentes" << endl;
        cout << " 5 Salir" << endl;
        cin >> opcion;

        switch(opcion) 
        {
        case 1: 
            cout << " --- Agendar cita --- " << endl;
            cout << " Ingrese el nombre del paciente" << endl;
            cin >> NdP;
            cout << " Ingrese el tratamiento" << endl;
            cin >> tratamiento;
            cout << " Ingrese la hora de tratamiento" << endl;
            cin >> HdT;
            cout << " Ingrese la descripcion del tratamiento" << endl;
            cin >> desc;
            cout << " Ingrese el precio unitario del tratamiento" << endl;
            cin >> PUT;
            cout << " Ingrece el precio unitario" << endl;
            cin >> PreU ;
            cout << " Ingrese la cantidad del tratamiento" << endl;
            cin >> CdT;
            cout << " ---------------------- " << endl;
            T = PreU * CdT;
            cout << "El total es:" << T << endl;



        }
      
    } while (opcion < 5);

    return 0;
}
