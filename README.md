# C-sharp-Lists
Random myRandom = new Random();

for (int index = 0; index < 10000; index++)
{
  int inputs = (int)(myRandom.NextDouble() * 50) + 1;
  myList.Add(inputs);
  if (index % 2000 == 0)
    {
      Console.WriteLine("\n");
    }
  Console.Write(myList[index] + " ");
}
Console.ReadLine();
