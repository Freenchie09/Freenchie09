#include <iostream>
using namespace std;
int main()
{
    string fps,
        moba,
        another_game;

    cout << "Do you want to play an fps game? ";
    cin >> fps;

    if (fps == "yes"  fps == "no")
    {
        cout << "Do you want to play a moba game instead? ";
        cin >> moba;
        if (moba == "yes"  moba == "no")
        {
            cout << "Do you want to play other games then? ";
            cin >> another_game;
            if (another_game == "yes"  another_game == "no")
            {
                cout << "\nHere are your video game choices choices:"
                    << endl;

                if (fps == "yes")
                {
                    if (moba == "yes")
                    {
                        if (another_game == "yes" 
                            another_game == "no")
                        {
                            cout << "   League of Legends\n";
                            cout << "   Dota\n";
                            cout << "   Teamfight Tactics\n";
                            cout << "   Roblox\n";
                            cout << "   Minecraft\n";
                            cout << "   Fornite\n"; 
                            cout << "   Valorant\n";
                            cout << "   Overwatch\n";
                            cout << "   CSGO\n";
                            cout << "   Arsenal\n";
                        }
                    }
                    else
{
                        if (another_game == "yes")
                        {
                            cout << "   Teamfight Tactics\n";
                            cout << "   Roblox\n";
                            cout << "   Minecraft\n";
                            cout << "   Fornite\n";
                        }
                        else
                        {
                            cout << "   Valorant\n";
                            cout << "   Overwatch\n";
                            cout << "   CSGO\n";
                            cout << "   Arsenal\n";
                        }
                    }
                }
                else
                {
                    if (moba == "yes")
                    {
                        if (another_game == "yes" ||
                            another_game == "no")
                        {
                            cout << "   League of Legends\n";
                            cout << "   Dota\n";
                        }
                    }
                    else
                    {
                        if (another_game == "yes")
                        {
                            cout << "   Teamfight Tactics\n";
                            cout << "   Roblox\n";
                            cout << "   Minecraft\n";
                            cout << "   Fornite\n";
                        }
                        else
                        {
                            cout << "   Watch a movie\n";
                            cout << "   Go workgout\n";
                            cout << "   Cook a meal\n";
                            cout << "   Go for a walk\n";
                            cout << "   Practice piano\n";
                        }
                    }
                }
            }
            else
else
            {
                cout << "\nError. "yes" or "no" must be chosen.\n"
                    << "Rerun the program and try again."
                    << endl;
            }
        }
        else
        {
            cout << "\nError. "yes" or "no" must be chosen.\n"
                << "Rerun the program and try again."
                << endl;
        }
    }
    else
    {
        cout << "\nError. "yes" or "no" must be chosen.\n"
            << "Rerun the program and try again."
            << endl;
    }
    system("pause>null");
    return 0;
}
