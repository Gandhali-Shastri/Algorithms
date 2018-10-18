# Algorithms

1. Longest common sub-sequence-
      Program to compute the longest common sub-sequence of two sequences in two different ways: Longest common sub-sequence and Longest        common strictly increasing sub-sequence.
     (-1 indicates new line)
      input -     9 9
                  7 8 9 9 8 7 7 8 9 -1 7 7 8 8 6 9 8 7 9 -1
      output -    789987789
                  778869879
                  LCS is 789879, length==6

      
2. Gomory-Hu Cut tree -
      Program to determine a cut tree for an undirected graph. The cut tree is to be found using the algorithm MGH on p. 152 of                 http://epubs.siam.org.ezproxy.uta.edu/doi/abs/10.1137/0219009 .  This technique uses a max-flow, min-cut implementation as an             “oracle”.
      The output cut tree, the smallest capacity on the unique path between vertices s and t gives the capacity of the minimum cut when s       and t are used as the source and sink for a network flow algorithm.
      input -     6 8               output -    NODE1  NODE2 MAXFLOW 
                  0 1 2                         1 2 8
                  0 2 1                         2 0 5
                  0 4 2                         3 2 9
                  1 2 4                         4 3 9
                  2 3 5                         5 4 5
                  3 4 5
                  4 1 2
                  4 5 5
      
3. longest common substring-
      The program is used to find the Longest Common Substring for three strings using suffix array and Longest Common Prefix.
Input - 
      String 1 -abcdefghijklmnopqkstukwfyzabcdefghijklmnoporstuvwjyzabcdsfghijklmnopqrstuwwxyzabcdemgaixklmnspqpstuvwxyzaccdefghijklmnopqrotbvwxyzabcdefghijklmnopqrstuvwxyzabcdefghijklmnopqrstuvvxyzabcdefghijklfnapqrstuvwsyzabcdefxhijrlmnypqjstuvwxyzabcdefghijklmnqpqrstuvwxozobcdefghijklmnopqrstuvwxyzabcdefghirklmnorqrstuvwxyzabcdcfghijvlmnopqrstuvwxyzajcdefghijklmnopqrstuvwxyzabcdefghizklmnopqrstuvwgyjabbdefghijkwmnopqrstuvwxyzebcdefghiuklmnopqratuvwxyzhbedexghijklmnopqrstuvwxyzabcdexghijklmnopqrxtuvlfyzabcdef
      String 2 -
  ghijklmcopvrstuqwxyzabcdefghiqklmnopvrstuvwxyzabcdefghijklmnopqrstuhwxyzabcdefnhijklmnopqrstuvwpyzabcdefghijkemnopqrstuqwxmzabndefrhijkpmnolmrwtkumxyzabcdefghijklmnolqrstuvwxyzabcdefghijklmnoxqrstvvsxyzabcdefghjjulmnopjrstuvwbyzabcdefghijklmnopqrstuvwxyzabcdefghijkltnopqrstuvwxyzafcdlbghiikpynopqrsmuvwxyzabcdefghijklqnopqrutuvwxyzaxcdefghijklwaopqrstsvwxyznbcjefghijklmgopqrstuvwxyzabcdefghidklmnopqgsmuvwxyzabcdefgvijkltnopqrstuvwxyzabcdefghijklmnopqrstuvwxyzabcdefghijklmnopqrstuvwxyzabcdefghijkl
  
      String 3 -
  mnopqrstncwxyzabcdefghijklmnopqrstuvwxyzabtdefghijclmnoparstuvnxyzabcdefgwijklmnopqostuvwxyzabcdefghijklmnopqrstuvwxyzabcdefghijkgmnopqrstuvzxyzabcdeaghijklmnopqrstuvwxyzabkdefghijblmnopqbstuvhxyzaasdefnhioklmnjpqrstlvwwyzabcdeflhijklmnopqrstuvwxyzabcdefghijkumnopqrstuvxxyzabcdefghijklmnopqrstuvwxyzabcdpfgeijklmnopqrstumwxyzqbvdefghijklmnopqrstuvlxyzakcdefghijkwvuoeqrctuvwxywabcdefghijklmnopqrstuvwxyzfbcdefghijklmgopqrscuvwxyzarcdefghijklmwopqrstuvwxyzabcdefghijklmnopqrstuvwxyzbbcdhfghijklmnrpqr
  
  OUTPUT -
      Length of longest common substring is 42
      x at 1245, y ends at 1246, z at 1247
      vwxyzabcdefghijklmnopqrstuvwxyzabcdefghijk
