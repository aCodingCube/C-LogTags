```c++
import std;
import LogTags;

int main()
{
	cLog::Logger logger = {};

	logger.createNewTag(cLog::LIGHT_YELLOW, "WARNING");

	logger.tag("WARNING");

	std::cout << "Wrong data type!" << std::endl; // ["WARNING"] Woring data type1

	return 0;
}
```
