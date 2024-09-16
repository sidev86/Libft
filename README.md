<h1> Libft </h1>

My first library written in C.
To create this library we had to redevelop typical functions of the <strong><em>libc</em></strong> library.
<br>The functions implemented in the library are the following:

<h2>Character Functions</h2>

<table border="1">
  <tr>
    <th>Function</th>
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
    <td>Checks if the character is an alphanumeric character</td>
  </tr>
   <tr>
    <td>isascii</td>
    <td>Checks if the character is an ASCII character</td>
  </tr>
   <tr>
    <td>isprint</td>
    <td>Checks if the character is a printable character</td>
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
    <td>Returns the length of the string s, excluding the NULL terminator (\0).</td>
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

</table>

<h2>Memory Functions</h2>

<table border="1">
  <tr>
    <th>Function</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>memset</td>
    <td>Fill a contiguous block of memory with a specific value.</td>
  </tr>
  <tr>
    <td>bzero</td>
    <td>Fills the first n bytes of the object pointed to with zeros</td>
  </tr>
  <tr>
    <td>memcpy</td>
    <td>Copy a block of memory from one location to another. Does not handle overlapping regions</td>
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


<h2>Skills learned</h2>

- Creation of a makefile
- Re-creation of libc library functions (string manipulation, operations on memory, writing data on files)
- Usage of pointers

Readme WIP ....


