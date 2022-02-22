# JS-Advanced

# Assignment 1:
1) Get battles.json via. AJAX call
From battle json provide following output

{
'most_active':{
    'attacker_king',
    'defender_king',
    'region',
    'name'
},
'attacker_outcome':{
    'win', // total win
    'loss' // total loss
},
'battle_type':[], // unique battle types
'defender_size':{
    'average',
    'min',
    'max'
    }
}



2) Use the following API to find the repository from git using git search API using ajax.
Consider input as the search parameter.
Visit this api to know moreI : https://developer.github.com/v3/search/
Api documentation : https://api.github.com/search/repositories?q={{input from text}}


From that api this output is expected:

{
	"name": "node",
      	"full_name": "nodejs/node",
      	"private": false,
	"owner":{
  		"login":"owner.login",
		"name":" API call to result.owner.url ",
            “followersCount”:”API call to result.owner.url”,
            ““followingCount”:”API call to result.owner.url”,”
        },
       “licenseName”:”license.name”,
       "score":”score”
       "numberOfBranch":"API call to result.branches_url and count the    result"
}



3) API: http://api.nobelprize.org/v1/prize.json ->
Fetch all data from API and find all the entries from year 2000 to 2019 and then find people who won prizes for category 'Chemistry'.

4) API: https://think.cs.vt.edu/corgis/datasets/json/airlines/airlines.json
Fetch all data from API and find all the cancelled, delayed, diverted, on time flights for all airports from API 2 and check if the sum is equal to the total value.
