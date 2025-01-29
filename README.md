# picalc (pi calculator)
This is a simple pi calculator package for python 3.10+.
It is written in Python and uses the Chudnovsky algorithm to calculate pi to a specified number of decimal places.
It is a simple and easy to use package that can be easily integrated into any Python project.
## Installation
To install the package, simply run the following command in your terminal:
```bash
pip install picalc
```
## Usage
To use the package, simply import the `picalc` module and call the 'Chudnovsky' class with the desired number of decimal places as an argument.
```python
import picalc

pi = picalc.Chudnovsky(100,'terminal') # calculate pi to 100 decimal places and print the result
print(pi)
```
You can also use the gui mode by passing 'gui' as the second argument to the 'Chudnovsky' class. This will open a window with a progress bar and a text box that displays the calculated value of pi.
```python
import picalc

pi = picalc.Chudnovsky(None,'gui') # you shouldn't pass any argument to the first parameter,because the gui mode will show a text box to enter the number of decimal places
```
## License
This package is licensed under the GNU General Public License v3.0.
You can find the full license text in the LICENSE file.
## Contributing
If you would like to contribute to this project, please feel free to submit a pull request or open an issue.
## Contact
If you have any questions or comments, please feel free to contact me at [my email](mailto:17818883308@139.com).
## Disclaimer
This package is provided "as is" without any warranty or guarantee of any kind. Use at your own risk.
## Acknowledgements
This package was created by [my name](https://github.com/your-username).
