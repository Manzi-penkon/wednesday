def is_palindrome(s):
    # Normalize the string: remove spaces and convert to lowercase
    normalized_str = ''.join(s.split()).lower()
    # Check if the string reads the same forwards and backwards
    return normalized_str == normalized_str[::-1]

# Example usage
print(is_palindrome("madam"))  # True
print(is_palindrome("noon"))   # True
print(is_palindrome("hello"))  # False
print(is_palindrome("A man a plan a canal Panama"))  # True
