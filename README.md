<!-- <p align="center">
    <img alt="" src=https://komarev.com/ghpvc/?username=odinglyn0&style=for-the-badge />
</p> -->

website: [odinglynn dot com](https://odinglynn.com)

<h2 align="center">About Me </h2>

```python
from typing import Tuple, List, Dict

class Attributes(Tekky):
    @property
    def contact(self) -> Tuple[str, str, str]:
        email    = "info@odinglynn.com"
        website  = "odinglynn.com"
	    
        return website, email

    @property
    def life(self) -> Tuple[List[str], int]:
        langs = ['Irish', 'English']
		
        return langs
	
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'expert'      : ['python'],
            'intermediate': ['go', 'js'],
            'learning'    : ['c++', 'rust', 'c#']
        }
        specialities  = ['white-hat hacking', 'fullstack', 'ml', 'steganography']
        ide           = ['vscode', 'pycharm']
        pc            = {
            'Windows': {
                'custom': {
                    'processor': 'AMD ryzen 5 4600g | 6 cores',
                    'ram'      : '32gb',
                    'gpu'      : 'internal | dont know the ammount of CUDA cores'
                }
            }
        }

	return langs, specialities, ide, pc
```
