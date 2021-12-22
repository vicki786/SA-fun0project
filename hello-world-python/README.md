###
# Copy of LaunchDarkly Sample Python Application as mentioned in https://docs.launchdarkly.com/guides/tutorials/sdk-flag

# Make sure, you have Python version 3.5 or higher.

## Build instructions 

1. Install the LaunchDarkly Python SDK by running `pip install requirements.txt`

2. Edit `hello-world.py` and set the value of `sdk_key` to your LaunchDarkly SDK key. If there is an existing boolean feature flag in your LaunchDarkly project that you want to evaluate, set `feature_flag_key` to the flag key.

```python
sdk_key = "1234567890abcdef"

feature_flag_key = "my-flag"
```

3. Run `python3 hello-world.py`.  You may need to run this command like `sudo python3 hello-world.py` if you have no admin permission on the user logged into the server.

You should see the message `"Hello World Feature flag '<flag key>' is <true/false> for this user"`.
