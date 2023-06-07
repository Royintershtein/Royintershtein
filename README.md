int i = 1;
int len = 0;
string hig;
string[] word = new string[i];

word[0] = Console.ReadLine();
len = word[0].Length;
hig = word[0];
while (word[i] != "stop")
{

    word[i] = Console.ReadLine();
    if (word[i].Length > len)
    {
        len = word[i].Length;
        hig = word[i];
    }
    i++;
}

Console.WriteLine("the word with the most letters is " + hig);
