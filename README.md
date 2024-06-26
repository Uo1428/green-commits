# 🧶 Green Commits

Automatically keep GitHub commit status green.

> a commit a day keeps your girlfriend away. **changed to** a commit a day keeps your girlfriend from going away. 😢


```diff
+ Use this template or the official one
1. Go to .github/workflows/cy.yml in your repository
2. Remove the # in line 7, 8
3. Go to https://github.com/yourGithubUsername/green-commits/settings/secrets/actions 
  3.1. Create a secret named EMAIL with your email
  3.2. Create a scret named NAME with your github username
4. Go to https://github.com/yourGithubUsername/green-commits/settings/actions and Give `Read and write` permissions to workflow
 
+ Enjoy the green Contribution Activity panel in your profile :D
```

## 📘 Developer Instructions

-Click the **Use this template** button in the upper right corner to copy this GitHub repository
- Modify [lines 7 and 8 of the ci.yml file](https://github.com/IMXNOOBX/green-commits/blob/master/.github/workflows/ci.yml#L7-L8) to remove the preceding ` #` sign
- ~~Modify [lines 19, 20 of the ci.yml file](https://github.com/IMXNOOBX/green-commits/blob/master/.github/workflows/ci.yml#L19-L20) to your own GitHub Account and Nickname~~
- (Optional) You can do this by modifying [line 8 of the ci.yml file](https://github.com/IMXNOOBX/green-commits/blob/master/.github/workflows/ci.yml#L8) Adjust frequency

The scheduled task syntax has 5 fields separated by spaces, each field representing a time unit.

```plain
    ┌────────────── minutes (0 - 59)
    │ ┌────────────── Hours (0 - 23)
    │ │ ┌────────────── Day (1 - 31)
    │ │ │ ┌────────────── Month (1 - 12 or JAN-DEC)
    │ │ │ │ ┌────────────── Week of the week (0 - 6 or SUN-SAT)
    │ │ │ │ │
    │ │ │ │ │
    │ │ │ │ │
    * * * * *
```

**Note**: Due to the limitation of GitHub Actions, if set to `* * * * *` , the actual execution frequency is once every 5 minutes.


## License && Credits

- Credits: [**justjavac**](https://github.com/justjavac)