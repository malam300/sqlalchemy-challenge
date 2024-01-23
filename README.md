I encountered an "OperationalError: unable to open database file" while working on the climate analysis. Despite attempting various solutions found through Google and ChatGPT, the issue persisted. 
Eventually, I found success by adding a file path (e.g., db_path = Path('../Downloads/hawaii.sqlite')) in line 4 of my code, following an alternative method mentioned in a class lecture. 
