# Ex05-Rec-JaggedArray
## Aim:
To write a C# program to create a sample CPU usage on a network with 4 nodes using a jagged array.
## Algorithm:
## Step 1:
Start the C# program in visual studio 2022.

## Step 2:
Declare a Jagged Array for four element.

## Step 3:
Initialize the elements.

## Step 4:
Accessing the elements.

## Step 5:
Finish the program and Run the prgram

## Step 6:
Take the screenshot of the output of the program.


## Program:
```
PROGRAM DEVELOPED BY: R.SOMEASVAR
REGISTER NUMBER: 212221230103
```
```
using System;
class jagged
{
    public static void Main(string[] args)
    {
        int[][] array = new int[4][];
        array[0] = new int[4];
        array[1] = new int[4];
        array[2] = new int[4];
        array[3] = new int[4];
        for (int i = 0; i < 4; i++)
        {
            for (int j = 0; j < array[i].Length; j++)
            {
                array[i][j] = i * j + 70;
            }
        }
        for(int i = 0; i < array[i].Length; i++)
            {
                for(int j=0; j < array[i].Length; j++)
                {
                    Console.WriteLine("CPU usage at node" + i + " is " + array[i][j] + "%");
                }
                Console.WriteLine();

            }
        
    }
}
```


## Output:
![exp5](https://user-images.githubusercontent.com/93434149/191890118-26996562-5894-42bf-972b-4692dcf9e07d.jpg)


## Result:
Thus, the C# program to create a sample CPU usage on a network with 4 nodes using a jagged array is executed successfully.


