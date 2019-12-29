# Usage

Note to self: captcha solvers are incredibly noisy now - one out of 3-5 does passes. Solving a one manually sort of guarantees the result. Sticking to a place and changing time selector needs no captcha as of now. Also lines are not so bad - I got my stuff sorted in under 3 hours

Have python3 installed

    brew install python3

Have pip3 installed

    brew install pip3

Have chromedriver installed

    brew install cask chromedriver

Install the required libs

    source venv/bin/activate
    ipython kernel install --user --name=ca-dmv-poll
    pip3 install -r requirements.txt

Start the thing

    jupyter notebook

In UI select Cell > Run All.

Profit!
