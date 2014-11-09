Common_Words
c++ file to declare common words

# include <iostream>
# include <string>

using namespace std;

string a[5][25] = 
{
	{ "time", "person", "year", "way", "day", "thing", "man", "world", "life",
	"hand", "part", "child", "eye", "woman", "place", "work", "week", "case",
	"point", "government", "company", "number", "group", "problem", "fact" },
	{"be", "have", "do", "say", "get", "make", "go", "know", "take", "see", 
	"come", "think", "look", "want", "give", "use", "find", "tell", "ask",
	"work", "seem", "feel", "try", "leave", "call"},
	{ "good", "new", "first", "last", "long", "great", "little", "own", "other",
	"old", "right", "big", "high", "different", "small", "large", "next", "early",
	"young", "important", "few", "public", "bad", "same", "able"},
	{ "to", "of", "in", "for", "on", "with", "at", "by", "from", "up", "about",
	"into", "over", "after", "beneath", "under", "above" },
	{"the", "and", "a", "that", "I", "it", "not", "he", "as", "you", "this",
	"but", "his", "they", "her", "she", "or", "an", "will", "my", "one", "all",
	"would", "there", "their"}
};

int main()
{
	string input;
	int x=0, y=0, c, b; 
	cin >> c >> b;

		if (c == 0 && b < 25)
			cout << "your word is a noun and is " << a[c][b] << endl;
		else if (c == 1 && b < 25)
			cout << "your word is a verb and is " << a[c][b] << endl;
		else if (c == 2 && b < 25)
			cout << "your word is an adjective and is " << a[c][b] << endl;
		else if (c == 3 && b < 25)
			cout << "your word is a preposition and is " << a[c][b] << endl;
		else if (c == 4 && b < 25)
			cout << "your word is another common word and is " << a[c][b] << endl;
		return 0;
}
============

Common words finder
