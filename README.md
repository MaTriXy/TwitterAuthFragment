TwitterAuthFragment
===================

Twitter auth api with single method call using android fragment.


Usage 
===================

``` java
TwitterAuthFragment.startTwitterAuth(this, CONSUMER_KEY, CONSUMER_SECRET, CALLBACK_URL,
	new TwitterAuthFragment.TwitterAuthListener() {
	
		@Override
		public void onSuccess(String oauthToken,
				String oauthVerifier) {
				// Here do whatever your like with oauthToken and oauthVerifier
		}

		@Override
		public void onFailure(Exception e) {
		    // Failure 
		}
	});
```

License
===================

    Copyright 2014 Rohit Kulkarni
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
     
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
