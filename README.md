"use strict"

var a,b,c;
for(a=1;a<=5;a++)
{
    for(b=5;b>=1;b--)
    {
        // document.write("<br>",a, "(a) and (b)",b);
        if(a == b)
        {
            document.write("*")
        }
        else
        {
            document.write("&nbsp;&nbsp")
        }
       
    }
    for(c=2;c<=5;c++)
    {
        // document.write("<br>",a, "(a)and (c)",c);

        if(a == c)
        {
            document.write("*")
        }
        else
        {
            document.write("&nbsp;&nbsp")
        }
    }
    document.write("<br>")
}

// second part
"use strict"
var a,b,c;
for(a=5;a>=1;a--)
{
    for(b=5;b>=1;b--)
    {
        // document.write("<br>",a, "(a) and (b)",b);
        if(a==b)
            document.write("*");
        else
            document.write("&nbsp;&nbsp");
    }
    for(c=2;c<=5;c++)
    {
        // document.write("<br>",a, "(a) and (c)",c);

        if(a==c)
            document.write("*");
        else
            document.write("&nbsp;&nbsp");
    }
    document.write("<br>")
}
