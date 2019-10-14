// object is reference type
public class Man inherits Human, Alien implements IItellect {
	public Man() {  }
	
    public get Name: String {

    }

	public function Human::Run (String[] str) -> Kwo // Explicitly
	{
		// ...
		return new Kwo();
	}
	
	public function Run (String[] str) -> auto // Implicitly
	{
		// ...
		return new Kwo();
	}
	
	~Man() {  }
}
