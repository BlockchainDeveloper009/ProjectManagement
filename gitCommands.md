# Frequently used Commands

$git status
$git add .
$git commit -m "commit message"
$git push

# create new branch

$git switch -c test origin/devbr 

--test (newbranch name) ; devbr (old/default branch name)

# add new files to new (test) branch

    --add a file addNft.sol with contract name testaddNft.sol which will be added only to new branch(test)
    $ git add .
    $ git commit -m "adding new file to test branch"
    $ git push origin HEAD:test
    -- test(new branch name, in this case test is new branch name)



# add new files to old (devbr) branch

    --add a file addNft.sol with contract name devbraddNft.sol which will be added only to new branch(devbr)
    $ git add .
    $ git commit -m "adding new file to devbr branch"
    $ git push origin HEAD:devbr
    -- devbr(old branch name) in this case devbr is new branch name)
