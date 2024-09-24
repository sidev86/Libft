<h1> Libft </h1>

<h2>Description</h2>

The scope of this project is making a library in C. This library is a collection of functions that will be useful for the next 42 projects.<br>
Some of these functions are a recreation of typical functions of the <strong><em>libc</em></strong> library, others are either not in <strong><em>libc</em></strong> or part of it but in a different way. 
<br>The functions implemented in the library are the following:

<h2>Character Functions</h2>

<table border="1">
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>isalpha</td>
    <td>Checks if the character is an alphabetic letter.</td>
  </tr>
  <tr>
    <td>isdigit</td>
    <td>Checks if the character is a decimal digit.</td>
  </tr>
  <tr>
    <td>isalnum</td>
    <td>Checks if the character is an alphanumeric character.</td>
  </tr>
   <tr>
    <td>isascii</td>
    <td>Checks if the character is an ASCII character.</td>
  </tr>
   <tr>
    <td>isprint</td>
    <td>Checks if the character is a printable character.</td>
  </tr>
   <tr>
    <td>toupper</td>
    <td>Converts the character to its uppercase equivalent if it's a lowercase letter.<br> If is not a lowercase letter, it returns unchanged.</td>
  </tr>
   <tr>
    <td>tolower</td>
    <td>Converts the character to its lowercase equivalent if it's an uppercase letter.<br> If is not an uppercase letter, it returns unchanged.</td>
  </tr>
</table>

<h2>String Functions</h2>

<table border="1">
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>strlen</td>
    <td>Returns the length of the string s, excluding the NULL terminator '\0'.</td>
  </tr>
  <tr>
    <td>strchr</td>
    <td>Searches for the first occurrence of the character in the string. Returns a pointer to the first occurrence of character, or NULL if character is not found.</td>
  </tr>
  <tr>
    <td>strrchr</td>
    <td>Searches for the last occurrence of the character in the string. Returns a pointer to the last occurrence of character, or NULL if character is not found.</td>
  </tr>
   <tr>
    <td>strncmp</td>
    <td>Compares up to n characters of the string s1 and string s2. Returns an integer less than, equal to, or greater than zero if string s1 is less than, equal to, or greater than string s2.</td>
  </tr>
   <tr>
    <td>strnstr</td>
    <td>Locates the first occurrence of the null-terminated string s2 in the string s1, where not more than n characters are searched. Characters that appear after a `\0' character are not searched.</td>
  </tr>
   <tr>
    <td>strlcpy</td>
    <td> Copies up to a length of characters passed as input, from a source string to a destination string, null-terminating the result. Returns the length of the source string.</td>
  </tr>
   <td>strlcat</td>
    <td> Appends up to a length of characters passed as input, from a source string to a destination string, null-terminating the result. Returns the total length of the string it tried to create.</td>
  </tr>

</table>

<h2>Memory Functions</h2>

<table border="1">
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>memset</td>
    <td>Fill a contiguous block of memory with a specific value.</td>
  </tr>
  <tr>
    <td>bzero</td>
    <td>Fills the first n bytes of the object pointed to with zeros.</td>
  </tr>
  <tr>
    <td>memcpy</td>
    <td>Copy a block of memory from one location to another. Does not handle overlapping regions.</td>
  </tr>
   <tr>
    <td>memmove</td>
    <td>Copy a block of memory from one location to another. Handles overlapping memory regions safely.</td>
  </tr>
   <tr>
    <td>memchr</td>
    <td>Searches for the first occurrence of byte character in the first n bytes of the memory area pointed to. Returns a pointer to the byte found, or NULL if the character is not found.
</td>
  </tr>
   <tr>
    <td>memcmp</td>
    <td>Compares the first n bytes of the memory areas s1 and s2. Returns an integer less than, equal to, or greater than zero if s1 is less than, equal to, or greater than s2.</td>
  </tr>
</table>

<h2>Other Functions</h2>

<table border="1">
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>atoi</td>
    <td>Converts a string to an integer. It stops converting when it encounters a non-numeric character and returns the integer value.</td>
  </tr>
  <tr>
    <td>calloc</td>
    <td>Allocates memory for an array of a a defined number of elements, each of which is size bytes long and automatically ensures that all bytes are initialized to zero. </td>
  </tr>
  <tr>
    <td>strdup</td>
    <td>Duplicates a string by allocating memory and copying the content of the original string into it.</td>
  </tr>
</table>


<h2>Additional Functions (not in libc)</h2>
<table border="1">
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>ft_substr</td>
    <td>Allocates and returns a substring from a string given . The substring begins at start index and is of maximum size len</td>
  </tr>
  <tr>
    <td>ft_strjoin</td>
    <td>Allocates and returns a new string, which is the result of the concatenation of a string with another string. </td>
  </tr>
  <tr>
    <td>ft_strtrim</td>
    <td>Allocates and returns a copy of a string, with the characters specified in ’set’ removed from the beginning and the end of the string.</td>
  </tr>
  <tr>
    <td>ft_split</td>
    <td>Allocates and returns an array of strings obtained by splitting the string using a character as a delimiter. The array must end with a NULL pointer.</td>
  </tr>
   <tr>
    <td>ft_itoa</td>
    <td>Allocates and returns a string representing the integer received as an argument. Negative numbers must be handled.</td>
  </tr>
    <tr>
    <td>ft_strmapi</td>
    <td>Applies a function to each character of a string, and passing its index as first argument to create a new string resulting from successive applications of the funtion.</td>
  </tr>
    <tr>
    <td>ft_striteri</td>
    <td>Applies the function on each character of the string passed as argument, passing its index as first argument. Each character is passed by address to the function to be modified if necessary.</td>
  </tr>
  <tr>
    <td>ft_putchar_fd</td>
    <td>Outputs a character to the given file descriptor.</td>
  </tr>
    <tr>
    <td>ft_putstr_fd</td>
    <td>Outputs a string to the given file descriptor.</td>
  </tr>
    <tr>
    <td>ft_putendl_fd</td>
    <td>Outputs the string to the given file descriptor followed by a newline.</td>
  </tr>
   <tr>
    <td>ft_putnbr_fd</td>
    <td>Outputs the integer to the given file descriptor.</td>
  </tr>
  
</table>


<h2>Usage</h2>

Type <code>make</code> to generate the library file <code>libft.a</code>. 
To use the library in your project just include the header file <code>"libft.h"</code>

<h2>Compilation instructions (gcc)</h2>

<code>gcc -o <strong><em>executable_name filename.c</em></strong> -L<strong><em>/path/to/lib</em></strong> -l:libft.a</code>


