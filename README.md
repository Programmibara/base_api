# base_api
# base class for api programms,
#
# encapsulate in subclass STORE, use for data storage
# write functions to initialize all types of databases, return the connection info as a dictionary and store in memory and storage redundant, restart connection with restart protocol
#   - decide based on optimisation
# write functions that connect to an initialized database, based on the connection info from a dictionary kept in memory or storage for shutdown 

FETCH necessary
PARSE necessary
# write functions that store parsed data in the connected database instance, use whats best for the case at hand



# encapsulate in subclass FETCH
# write functions to fetch data from all types of apis, when given connection details, store connection details in a dict
# 
# write functions that fetch data from the database, based on user input or memory or storage

# write functions that parse data from apis to a common type, prefer dictionarys 
# 

# encapsulate fetch functions in class attributes that fetch the requested data from api only if there is no database available
# store data in class attributes, and hide the functions for easy access, 
# store class attributes in a database initialized earlier add class method SAVE that can save a given dataset in the best database possible, optimize by total resource usage
# 
# add functions to vizualize and analyze fetched data, recursively, with user input
# add functions to store analyzed datasets, 
# add a section for user defined methods, basically a workspace with data analysis methods,  

#
#
#
#
#
#
# add a name attribute to class initialisation that holds info about api provider,
# add a list of endpoints
# ##
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
