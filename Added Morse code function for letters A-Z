#include <iostream>
#include <string>
#include <cctype>

using namespace std;

// Function to convert a letter to Morse code
string morseCode(char ch)
{
    switch(ch)
    {
        case 'A': return ".-";
        case 'B': return "-...";
        case 'C': return "-.-.";
        case 'D': return "-..";
        case 'E': return ".";
        case 'F': return "..-.";
        case 'G': return "--.";
        case 'H': return "....";
        case 'I': return "..";
        case 'J': return ".---";
        case 'K': return "-.-";
        case 'L': return ".-..";
        case 'M': return "--";
        case 'N': return "-.";
        case 'O': return "---";
        case 'P': return ".--.";
        case 'Q': return "--.-";
        case 'R': return ".-.";
        case 'S': return "...";
        case 'T': return "-";
        case 'U': return "..-";
        case 'V': return "...-";
        case 'W': return ".--";
        case 'X': return "-..-";
        case 'Y': return "-.--";
        case 'Z': return "--..";
        default: return "";
    }
}

int main()
{
    string message;
    string fullMessage = "";

    cout << "Enter a message in English: ";
    getline(cin, message);

    cout << "\nOutput Morse code:\n" << endl;

    for(int i = 0; i < message.length(); i++)
    {
        char ch = toupper(message[i]);

        // Ignore spaces and non-alphabet characters
        if(ch >= 'A' && ch <= 'Z')
        {
            string code = morseCode(ch);

            cout << ch << ": " << code << endl;

            fullMessage += code + "   ";
        }
    }

    cout << "\nFull Morse code with spaces:\n";
    cout << fullMessage << endl;

    return 0;
}
