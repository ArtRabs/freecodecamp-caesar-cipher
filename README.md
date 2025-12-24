# freeCodeCamp Python - Caesar Cipher

A step-by-step implementation of the Caesar cipher for the freeCodeCamp Python Certification.

## Quick start

Run the main file:

    python caesar_cipher.py

**Requires:** Python 3.8+

## Progress

- [x] Step 1: feat(caesar): step1 add shift variable
- [x] Step 2: feat(caesar): step2 add alphabet string
- [x] Step 3: feat(caesar): step3 create shifted_alphabet and print
- [x] Step 4: feat(caesar): step4 implement wraparound using slicing and concatenation
- [x] step 5: refactor(caesar): step5 remove print statement for shifted_alphabet
- [x] step 6: feat(caesar): step6 create translation table using str.maketrans
- [x] step 7: feat(caesar): step7 add sample text variable for encryption
- [x] step 8: feat(caesar): step8 encrypt text using translation_table
- [x] step 9: feat(caesar): step9 print encrypted output
- [x] step 10: feat(caesar): step10 wrap encryption logic into caesar function
- [x] step 11: feat(caesar): step11 add text and shift as parameters and remove text and shift in function body
- [x] step 12: feat(caesar): step12 call caesar with sample input
- [x] step 13: feat(caesar): step13 call caesar and print result
- [x] step 14: feat(caesar): step14 return translation directly and remove print
- [x] step 15: feat(caesar): step15 include uppercase mapping in translation_table
- [x] step 16: feat(caesar): step16 add validation stub for shift and return error message
- [x] step 17: feat(caesar): step17 validate shift with isinstance check
- [x] step 18: feat(caesar): step18 use not operator with isinstance to validate shift
- [x] step 19: feat(caesar): step19 validate shift is positive and return error message
- [x] step 20: feat(caesar): step20 validate shift is between 1 and 25 and update error message
- [x] step 21: feat(caesar): step21 add encrypt parameter with default True
- [x] step 22: feat(caesar): step22 support decrypt by negating shift when encrypt is False
- [ ] step 23: feat(caesar): step23 add encrypt and decrypt wrapper functions
- [ ] step 24: feat(caesar): step24 replace direct caesar call with encrypt wrapper
- [ ] step 25: feat(caesar): step25 test decrypt with sample input and print result

## Files of interest

- **caesar_cipher.py** - main implementation and step history

## How I track progress

I use commit messages as step markers. Example pattern:

    feat(caesar): step1 add shift variable
    docs(readme): <description>
    feat(caesar): <description>
    docs(readme): <description>
    ...

## Attribution

This project follows the freeCodeCamp Caesar Cipher exercise; implementation and notes are my work.

## License

MIT

## Author

ArtRabs
