function Run[T](str: T[]) -> T... // Explicitly
{
	// ...
	return Kwo{};
}

function Run[T, i: int](str: T[]) -> Iterator<T> // Explicitly
{
	// ...
	return Kwo{};
}

function Run[T](str: T[]) -> Future<T>... // Explicitly
{
	// ...
	return Kwo{};
}

function Run[T](str: T[]) -> Iterator<Future<T>> // Explicitly
{
	// ...
	return Kwo{};
}

function Run[T](str: T[]) -> T^... // Explicitly
{
	// ...
	return Kwo{};
}

suspend function Run[T](T[] str, type) -> Iterator[Future[T]] // Explicitly
{
	// ...
	T^ t = await GetMoney();
	var t = await GetMoney();
	return Kwo{};
}

public function Run (T[] str, type) -> Future[T]... // Explicitly
{
	// ...
	return Kwo{};
}