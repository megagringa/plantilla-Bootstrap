# ejercicioTema8

Ejercicio básico realizado en java (bootcamp) 


```
public class Persona {

        //Atributos
        private String nombre;
        private int edad;
        private int telefono;


	public Persona(){
                
        }

	public Persona(Persona persona){
                this.nombre=persona.nombre;
                this.edad=persona.edad;
                this.telefono=persona.telefono;
        }
	public Persona(String nom, int edad, int tel){
                this.nombre=nom;
                this.edad=edad;
                this.tel=tel;
        }

	public String mostrarDatos(Persona persona){
                String datos="Los datos son: \n";
                datos+=persona.nombre+"\n";
                datos+=persona.edad+"\n";
                datos+=persona.telefono+"\n";
                return datos;
        }
	

	public String getNombre() {
                return nombre;
        }
        public void setNombre(String nombre) {
                this.nombre = nombre;
        }

	public int getEdad() {
                return edad;
        }
        public void setEdad(int edad) {
                this.edad = edad;
        }

	public int getTelefono() {
                return telefono;
        }
        public void setTelefono(int edad) {
                this.telefono = telefono;
        }



public class Principal {

        public static void main(String[] args) {
                
                //Guardamos los datos
                Persona persona=new Persona();
                persona.setNombre("Juan");
                persona.setEdad(28);
                persona.setTelefono(124567);
                
                //Obtenemos los datos y los imprimimos
                String nombre=persona.getNombre();
                int edad=persona.getEdad();
                int telefono=persona.getTelefono();
                
                System.out.println("Los datos de la persona son: "+nombre+", "+edad+", "+telefono);
        }
        

}
```
