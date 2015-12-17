# wordpress-goodies

Problème des iframe sur les réseaux de site
Sur un réseau de site, le placement du <iframe> ne marchera pas à part pour le Super Admin. Même si un utilisateur est Administrateur sur un des sites du réseau, cela ne fonctionnera pas. Le seul moyen est d’ajouter cette ligne de code dans le fichier wp-config.phpde l’installation principale.

define( 'DISALLOW_UNFILTERED_HTML', true );
