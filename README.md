An sample of Python libraries on GitHub.

```console
$ pip install -e .                              
$ pip freeze                                    
# Editable install with no version control (veronica==0.1)                             
-e /home/apua/apualib                                     
$ pip uninstall veronica                                                                 
                                                                                       
$ pip install -e .                                                                     
$ pip freeze                                     
-e git+ssh://git@github.com/apua/mylib.git@96b2453e7654a513783633e123740a95ee72e685#egg=veronica
$ pip uninstall veronica                                                                        
                                                                                          
$ pip install git+ssh://git@github.com/apua/mylib
$ pip freeze                                                                                    
veronica @ git+ssh://git@github.com/apua/mylib@96b2453e7654a513783633e123740a95ee72e685
$ pip uninstall veronica                                                               
                                                                                       
$ pip install git+ssh://git@github.com/apua/mylib@main                                 
$ pip freeze                                                                           
veronica @ git+ssh://git@github.com/apua/mylib@96b2453e7654a513783633e123740a95ee72e685
$ pip uninstall veronica
                                                
$ tree hulkbuster/                              
hulkbuster/                                     
└── pyproject.toml                              
$ pip install git+ssh://git@github.com/apua/mylib@main#subdirectory=hulkbuster
$ pip freeze                                    
hulkbuster @ git+ssh://git@github.com/apua/mylib@6d16e3d4d14bf29ec88bfb6604f9c6df09b21709#subdirectory=hulkbuster
$ pip uninstall hulkbuster
```
