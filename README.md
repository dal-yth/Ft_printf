# Ft_printf
42 school algorithm project.

Score 112/100


The goal of this project is to learn about variadic functions and to train display options managements skills. 

### Features
- Re-code of printf, sprintf and dprintf
- Supports conversions %cspdiouxfb
- Supports specifiers h, hh, l, ll, j, z, L
- Supports flags #, 0, -, +, ' '
- Support for width and precision
- Support for asterisk (*)
- Support for %%
- Colours, ex. %{RED} %{EOC}

### Using ft_printf

Ft_printf is designed to be used exactly the same way as you would use normal printf and it's output is designed to match the printf on our schools iMacs. To see the full usage you can give ft_printf "%help" as format string and it will print out full usage.

### Conversions
![Specifiers](/images/ft_printf.jpg)
In the image above, you can see how specifiers affect different conversions.

### Note
My implementation of ft_printf requires my libft since we are not allowed to use any standard library functions. If you wish to test it out, head over to: 
#### [My libft repository](https://github.com/jmakela42/Libft)
