### C++ Module for Console Tags

```c++
import std; // for std::cout
import LogTags;

int main()
{
	cLog::Logger logger = {};

	logger.createNewTag(cLog::LIGHT_YELLOW, "WARNING");

	logger.tag("WARNING");

	std::cout << "Wrong data type!" << std::endl; // ["WARNING"] Woring data type!

	return 0;
}
```
