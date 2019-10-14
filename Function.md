external function Run (str: String[]) -> Kwo // Explicitly
{
	// ...
	return new Kwo();
}

internal function Run (str: String[]) // Implicitly
{
	// ...
	return Kwo{};
}

function Run (str: String[]) // Implicitly external
{
	// ...
	return Kwo{};
}

function Run (str: String[?]) -> (int, String) // Explicitly
{
	// ...
	return 1, "Some string";
}

function Run (str: String[]) -> (int, String) {
	// ...
	return 1, "Some string";
}

function Run (str: String[]) -> (int, String) {
	// ...
	Run
	return 1, "Some string";
}

function Run (fun: () -> ?) -> (int, String) {
	// ...
	fun();
	return 1, "Some string";
}