user: hypercorn UsersApi --reload --debug --bind UsersApi.local.gd:$PORT --access-logfile - --error-logfile - --log-level DEBUG
game: hypercorn WordleGameApi --reload --debug --bind WordleGameApi.local.gd:$PORT --access-logfile - --error-logfile - --log-level DEBUG
leaderboard: hypercorn leaderboardApi --reload --debug --bind leaderboardApi.local.gd:$PORT --access-logfile - --error-logfile - --log-level DEBUG
