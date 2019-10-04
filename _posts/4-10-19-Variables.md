---
layout: post
title: Variables!
categories: C# Programming
---
Today we used variables in our code yay us heres an example :

A varaiable is a variable is a value that can change, depending on conditions or on information passed to the program.
           
           
           
           {
                const double PoundsToDollarRate = 1.23;
                const double DollarsToPoundsRate = 0.81;

                Console.WriteLine("What is your username?");
                string UserName = Console.ReadLine();

                Console.WriteLine("Enter [1] to convert pounds to dollars  or [2] dollars to pounds");
                int Option = Convert.ToInt32(Console.ReadLine());

                Console.WriteLine("Enter the value you wish to convert?");
                double ConvertValue =Convert.ToDouble(Console.ReadLine());


                switch (Option)
                {
                   
                    case (1):
                    { 
                    double finalvalue = ConvertValue * PoundsToDollarRate;
                    Console.WriteLine(finalvalue + " is how many dollars you would have");
                    Console.ReadLine();
                    break;
                    }

                     
                    case (2):
                    { 
                    double finalvalue = ConvertValue * DollarsToPoundsRate;
                    Console.WriteLine(finalvalue + " is how many pounds you would have");
                    Console.ReadLine();
                    break;
                    }
                }
