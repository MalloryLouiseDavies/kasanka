#### UPDATE FILE PATH ######

# Check your current working directory
current_dir = os.getcwd()
print(f"Current working directory: {current_dir}")

# Change the working directory to the appropriate path
# If using Stoner_lab One Drive files, UPDATE "C:\Users\mallo\" with local synced path
os.chdir(r"C:\Users\mallo\OneDrive - University of Arizona\Stoner_lab - Documents\Stoner Lab Home\Projects\Automated Count Project\bighatchet")

# Check your current working directory
current_dir = os.getcwd()
print(f"Current working directory: {current_dir}")

### CREATING FOLDER EXAMPLE FOR WINDOWS ###
camera = 'thermal'
date = '20Jul'
images_folder = f'bighatchet-bats\\frames\\{date}\\{camera}'
print(images_folder)

# When Importing functions this can help
import sys
#sys.path.append('.../bats-code')
sys.path.append(f'bats-code')
