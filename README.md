    # Greeting messages
    set powered_msgs \
        "Be yourself; everyone else is already taken. - Oscar Wilde" \
        "So many books, so little time. - Frank Zappa" \
        "A room without books is like a body without a soul. - Marcus Tullius Cicero" \
        "If you tell the truth, you don't have to remember anything. - Mark Twain" \
        "I have not failed. I've just found 10,000 ways that won't work. - Thomas A. Edison" \
        "If you judge people, you have no time to love them. - Mother Teresa" \
        "If you can't explain it to a six year old, you don't understand it yourself. - Albert Einstein" \
        "Never trust anyone who has not brought a book with them. - Lemony Snicket" \
        "If you can make a woman laugh, you can make her do anything. - Marilyn Monroe" \
        "Not all those who wander are lost. - J.R.R. Tolkien" \
        "Do one thing every day that scares you. - Eleanor Roosevelt" \
        "There is nothing to writing. All you do is sit down at a typewriter and bleed. - Ernest Hemingway" \
        "Some day you will be old enough to start reading fairy tales again. - C.S. Lewis" \
        "Knowing yourself is the beginning of all wisdom. - Aristotle" \
        "The only true wisdom is in knowing you know nothing. - Socrates" \
        "A day without laughter is a day wasted. - Nicolas Chamfort" \
        "Those who don't believe in magic will never find it. - Roald Dahl" \
        "Happiness is not something ready made. It comes from your own actions. - Dalai Lama" \
        "Whatever you are, be a good one. - Abraham Lincoln" \
        "At the touch of a lover, everyone becomes a poet. - Plato" \
        "It's only after we've lost everything that we're free to do anything. - Chuck Palahniuk" \
        "One day I will find the right words, and they will be simple. - Jack Kerouac" \
        "Always do what you are afraid to do. - Ralph Waldo Emerson" \
        "Somewhere, something incredible is waiting to be known. - Carl Sagan" \
        "The unexamined life is not worth living. - Socrates" \
        "Why fit in when you were born to stand out? - Dr. Seuss" \
        "If you have a garden and a library, you have everything you need. - Cicero" \
        "Show me a hero, and I'll write you a tragedy. - F. Scott Fitzgerald" \
        "What you seek is seeking you. - Rumi" \
        "The road to hell is paved with adverbs. - Stephen King" \
        "If you look for perfection, you'll never be content. - Leo Tolstoy" \
        "Fear cuts deeper than swords. - George R.R. Martin" \
        "The journey of a thousand miles begins with a single step. - Lao Tzu" \
        "If you go home with somebody, and they don't have books, don't fuck 'em! - John Waters"

    # Pick a random quote
    set count (count $powered_msgs)
    set random_index (random 1 $count)
    set random_quote $powered_msgs[$random_index]

    # Print the random quote
    echo $random_quote
end
