# ProxyMesh Setup
ProxyMesh IP addresses are manually added to proxies.txt. Ensure you have a valid ProxyMesh account and use the IPs from your ProxyMesh dashboard.

# Run the application
-Clone the project or download the zip file and extract
- refer requirments.txt to install packages
-command : python server.py [in your terminal]
- activate python environment (venv) for better results

# Troubleshooting
If you encounter unusual login challenges from Twitter, try the following:
-Trying changing the username and password from server.py:
     WebDriverWait(driver, 60).until(
            EC.visibility_of_element_located((By.CSS_SELECTOR, "input[name='text']"))
        ).send_keys("blaash2512")
        WebDriverWait(driver, 60).until(
            EC.element_to_be_clickable((By.XPATH, "//span[text()='Next']"))
        ).click()
        WebDriverWait(driver, 60).until(
            EC.visibility_of_element_located((By.CSS_SELECTOR, "input[name='password']"))
        ).send_keys("Bblaash2512")
-Once you give your 'X(formely Twitter)' account credentials, it asks for confirmation/verification.. you can verify and commence.

If there's anything specific you need to adjust or add, let me know!