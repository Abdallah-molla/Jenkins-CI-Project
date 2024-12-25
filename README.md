# jenkins ci pipeline to trigger automatic pull requests
# firstly, setup ec2 instance on aws then install jenkins on aws 
# 2- in jenkins server install pull request builder plugin
# 3- configure pull request builder from manage jenkins on jenkins server
# 4- on github account configure webhook to trigger pull request automatic on jenkins server to run pipeline
# 5- create pipeline on jenkins server and put github project url and enable pull requset
# 6- modify any file on github repo and make new branck called testing-ci and then push change on testing-ci branch and then accept pull request on github
# 7- once you accept pull request , pipeline will build automatic